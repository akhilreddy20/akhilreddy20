### Hi, I'm Akhil Reddy 👋

Software Engineer based in Hyderabad, India. I like the parts of systems that have to stay correct when things go wrong: retries, idempotency, concurrent updates and access control.

**Featured work**

- **[eventually-consistent-form](https://github.com/akhilreddy20/eventually-consistent-form)**: exactly-once form submission over an unreliable network. Idempotency keys with in-flight de-duplication (a 50-concurrent-request test asserts a single record), retries with exponential backoff and full jitter, request fingerprinting (422 on key reuse), and a written trade-off analysis. Express · React · node:test · GitHub Actions · Docker
- **[lead-mgmt-system](https://github.com/akhilreddy20/lead-mgmt-system)**: CRM for an admissions team. Atomic optimistic locking, race-free lead assignment, per-lead authorization, private file uploads and conversion that happens exactly once. Integration tests run against real MongoDB in CI. Node · MongoDB · React + TypeScript · Docker Compose
- **[LedgerFlow](https://github.com/akhilreddy20/ledgerflow)**: Event-driven distributed payments ledger built with NestJS microservices, PostgreSQL, Kafka and Redis.Double-entry ledger using row-level locking with deterministic lock ordering: no double-spend, no deadlocks under concurrency.Orchestrated saga with compensation, plus transactional outbox and idempotent inbox for exactly-once effect over Kafka.
Idempotency keys, retries with backoff and jitter, circuit breaker on the PSP, and dead-letter topics with replay.
OpenTelemetry, Prometheus and Grafana observability, Kubernetes with KEDA lag-based autoscaling, k6 load and chaos testing.
**Tech:** TypeScript / JavaScript · Node.js (Express) · NestJs · RESTAPI · React · ReactNative · MongoDB · PostgreSQL · Docker · GitHub Actions

[LinkedIn](https://linkedin.com/in/akhilreddy20) · [Portfolio](https://akhil-portfolio-three-mu.vercel.app/) · [X](https://twitter.com/Akhilreddy1817)
