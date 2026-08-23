## Sidy Ndiaye

CS + Economics @ NC State (May 2028). Looking for a **Software Engineering internship for Summer 2027**.

Mostly backend — APIs, distributed systems, and the infrastructure they run on. What interests
me most is designing APIs that solve a real problem for whoever's calling them, and making sure
what I build holds up when something breaks.

### Projects

- **[Distributed Webhook Delivery Service](https://github.com/sidyn4444/webhook-delivery-service)** —
  Java 21 + Spring Boot 3. Sends HTTP callbacks to servers you don't control, without
  losing events when those servers are slow, down, or broken. Redis-backed queue with
  at-least-once delivery, backoff retries, a dead-letter queue, HMAC-SHA256 signing,
  SSRF-checked URLs, and a recovery sweep that puts jobs from dead workers back on the
  queue. Deployed and measured on AWS EKS: 178 deliveries/sec sustained at 4.8 ms p95,
  with zero events lost when a worker was killed mid-delivery.

- **[Intraday Trading App](https://github.com/sidyn4444/Intraday-Trading-App)** —
  Python + FastAPI full-stack app that screens roughly 10K stocks against 8
  technical filters, runs 4 automated trading strategies on user-selected stocks, and executes
  bracket orders through a broker API. SQLite-backed, cron-scheduled, with
  position close-outs scheduled at the end of the day. Strategies used: opening range breakout/breakdown
  and Bollinger Bands long/short.

- **WolfCafe** — Spring Boot + JPA/Hibernate + React + MySQL full-stack ordering and inventory
  system for a campus coffee shop. Built as the primary backend developer on a four-person team
  for NC State CSC 326. Owned the customer order lifecycle (PLACED → FULFILLED → PICKED_UP),
  tax rate system, and admin user management endpoints, plus role-based authorization for
  Customer, Staff, and Admin roles on top of the team's JWT auth, and the React login interface.
  *(Course team repository — source available on request.)*



### Stack

- **Languages** — Java · Python · JavaScript · SQL · Bash
- **Backend** — Spring Boot · Spring Security · JPA/Hibernate · FastAPI · REST APIs
- **Frontend** — React · HTML · CSS
- **Data** — PostgreSQL · Redis · MySQL · SQLite · Flyway · pandas · NumPy
- **Infrastructure & Observability** — AWS (EKS · ElastiCache · RDS · IAM) · Docker · Kubernetes · Helm · Micrometer · Prometheus · Grafana
- **Testing & Tooling** — JUnit 5 · Mockito · pytest · Maven · GitHub Actions · Git

### Reach me

sidyn4444@gmail.com · [LinkedIn](https://www.linkedin.com/in/sidyn4444/)
