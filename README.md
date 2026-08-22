## Sidy Ndiaye

CS + Economics @ NC State (May 2028). Looking for a **Software Engineering internship for Summer 2027**.

Mostly backend — distributed systems, APIs, and the infrastructure they run on. What interests
me most is what happens when things fail: retries, recovery, and proving a system held up
instead of assuming it did.

### Projects

- **[Distributed Webhook Delivery Service](https://github.com/sidyn4444/webhook-delivery-service)** —
  Java 21 + Spring Boot 3. Sends HTTP callbacks to servers you don't control, without
  losing events when those servers are slow, down, or broken. Redis-backed queue with
  at-least-once delivery, backoff retries, a dead-letter queue, HMAC-SHA256 signing,
  SSRF-checked URLs, and a recovery sweep that reclaims work from workers that die
  mid-delivery. **Deployed and measured on AWS EKS: 178 deliveries/sec sustained at
  4.8 ms p95, zero event loss under worker-kill testing** — method and limitations in
  the repo.

- **[Intraday Trading App](https://github.com/sidyn4444/Intraday-Trading-App)**
  ([live demo](https://intraday-trading-app.up.railway.app)) —
  Python + FastAPI full-stack app that screens roughly 10K stocks against 8
  technical filters, runs 4 automated trading strategies, and executes
  bracket orders through a broker API. SQLite-backed, cron-scheduled, with
  end-of-day position close-outs. Strategies: opening range breakout/breakdown
  and Bollinger Bands long/short.

- **WolfCafe** — Spring Boot + React + MySQL fullstack ordering and inventory system for
  a campus coffee shop. Built as the primary backend developer on a four-person
  team for NC State CSC 326. Owned the customer order lifecycle, tax rate
  subsystem, and admin user management endpoints. JWT auth with role-based
  authorization across Customer, Staff, and Admin roles. *(Course team repository — source available on request.)*

### Stack

- **Languages** — Java · Python · JavaScript · SQL · Bash
- **Backend** — Spring Boot · Spring Security · JPA/Hibernate · FastAPI · JWT · REST APIs
- **Data** — PostgreSQL · Redis · MySQL · SQLite · Flyway · pandas · NumPy
- **Infrastructure & Observability** — AWS (EKS · ElastiCache · RDS · IAM) · Docker · Kubernetes · Helm · Micrometer · Prometheus · Grafana
- **Testing & Tooling** — JUnit 5 · Mockito · pytest · Maven · GitHub Actions · Git

### Reach me

sidy4444@gmail.com · [LinkedIn](https://www.linkedin.com/in/sidyn4444/)
