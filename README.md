# Raphael Antioquia

Backend-focused full-stack software developer based in Toronto, Canada. I build applications with an emphasis on database integrity, application security, concurrency, and software reliability.

Previously a software developer at Info-Tech Research Group, contributing to an existing Ruby on Rails and React codebase. Computer Programming and Analysis graduate from Seneca Polytechnic (4.0 GPA), with over six years of professional nursing experience.

## Featured Projects

### [TriageHarbor](https://github.com/raphael-antioquia/triageharbor) — Incident Monitoring System

**Java 21 · Spring Boot · PostgreSQL · React · Flyway · Docker**

Receives authenticated application error events, aggregates them into incidents by fingerprint, and displays them through a React dashboard.

- **Concurrency & reliability:** Atomic PostgreSQL upserts verified through 50-call concurrent integration tests, with transactional rollback testing.
- **Database security:** Separate administrator, migrator, and application roles, validated by a 47-check privilege contract and 20 deliberate-violation test cases.
- **API protection:** Hashed and revocable ingest credentials, global and per-project token bucket rate limiting, request-size enforcement, and pattern-based sensitive-data redaction.
- **Infrastructure:** Automated quality checks and container publishing through GitHub Actions and GHCR; deployed and acceptance-tested on DigitalOcean using Docker Compose and Caddy HTTPS.

[Architecture](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/architecture.md) · [Database](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/database.md) · [Testing](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/testing.md)

### [TimeMetrics](https://github.com/raphael-antioquia/timemetrics) — Time Tracking & Productivity Analytics

**Next.js · React · TypeScript · PostgreSQL · Supabase**

A full-stack application featuring persistent timers, manual time entry, session history, and timezone-aware productivity analytics.

- **Application security:** Database-enforced user isolation through row-level security, least-privilege grants, and default-deny SQL function permissions.
- **Data integrity:** PostgreSQL GiST exclusion constraints prevent overlapping time entries, while composite foreign keys enforce ownership boundaries.
- **Full-stack engineering:** Server Components, Server Actions, authenticated user-scoped timer persistence, and failed-save recovery workflows.
- **Testing & analytics:** Timezone-aware SQL reporting tested across daylight-saving transitions, with automated Vitest and pgTAP suites running in CI.

[Architecture](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/architecture.md) · [Database](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/database.md) · [Testing](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/testing.md)

## Technical Skills

**Languages:** Java, TypeScript, JavaScript, Ruby, SQL  
**Backend:** Spring Boot, Ruby on Rails, Node.js, Express, REST APIs, JDBC  
**Frontend:** React, Next.js, Tailwind CSS  
**Databases:** PostgreSQL, Supabase, Flyway  
**Testing:** JUnit, Testcontainers, Mockito, Vitest, pgTAP  
**DevOps:** Docker, GitHub Actions, GHCR, Linux, Caddy  
**Observability:** Sentry, Micrometer, Spring Boot Actuator

## Contact

Open to backend and full-stack software development opportunities in Toronto/GTA and across Canada.

[LinkedIn](YOUR_LINKEDIN_URL)
