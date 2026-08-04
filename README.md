## Sidy Ndiaye

CS @ NC State. Looking for a Software Engineering internship for Summer 2027.

### Projects

- **[Distributed Webhook Delivery Service](https://github.com/sidyn4444/webhook-delivery-service)** —
  Java 21 + Spring Boot 3 service that delivers HTTP webhooks reliably to third-party
  endpoints. Redis-backed reliable queue with at-least-once delivery, exponential
  backoff with jitter, a dead-letter queue, and a recovery sweep that reclaims jobs
  from workers killed mid-delivery. Every payload is HMAC-SHA256 signed, and every
  subscriber URL is validated against the IP it resolves to (SSRF defense).
  Kubernetes and AWS EKS deployment in progress.


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

**Languages** — Java · Python · JavaScript · SQL · Lua
**Backend** — Spring Boot · Spring Security · JPA/Hibernate · FastAPI · JWT · REST APIs
**Data** — PostgreSQL · Redis · MySQL · SQLite · Flyway · pandas · NumPy
**Testing & Tooling** — JUnit 5 · Mockito · pytest · Docker · Maven · GitHub Actions · Git


### Reach me

- Email: sidy4444@gmail.com
- LinkedIn: https://www.linkedin.com/in/sidy-ndiaye-412228284/
