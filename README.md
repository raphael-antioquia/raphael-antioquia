# Hi, I'm Raphael Antioquia 👋

**Backend-focused Full-Stack Software Developer**

📍 Toronto, Canada

I build applications with an emphasis on database integrity, application security, concurrency, and software reliability.

Previously a software developer at Info-Tech Research Group, contributing to an existing Ruby on Rails and React codebase.

Computer Programming and Analysis graduate from Seneca Polytechnic (4.0 GPA), with over six years of professional nursing experience.

---

## 🚀 Featured Projects

### 🛡️ [TriageHarbor](https://github.com/raphael-antioquia/triageharbor) — Incident Monitoring System

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Receives authenticated application error events, aggregates them into incidents by fingerprint, and displays them through a React dashboard.

- **Concurrency & reliability:** Atomic PostgreSQL upserts verified through 50-call concurrent integration tests, with transactional rollback testing.
- **Database security:** Separate administrator, migrator, and application roles, validated by a 47-check privilege contract and 20 deliberate-violation test cases.
- **API protection:** Hashed and revocable ingest credentials, global and per-project token bucket rate limiting, request-size enforcement, and pattern-based sensitive-data redaction.
- **Infrastructure:** Automated quality checks and container publishing through GitHub Actions and GHCR; deployed and acceptance-tested on DigitalOcean using Docker Compose and Caddy HTTPS.

📚 **Documentation:** [Architecture](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/architecture.md) · [Database](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/database.md) · [Testing](https://github.com/raphael-antioquia/triageharbor/blob/main/docs/testing.md)

### ⏱️ [TimeMetrics](https://github.com/raphael-antioquia/timemetrics) — Time Tracking & Productivity Analytics

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-25865D?style=flat-square&logo=supabase&logoColor=white)

A full-stack application featuring persistent timers, manual time entry, session history, and timezone-aware productivity analytics.

- **Application security:** Database-enforced user isolation through row-level security, least-privilege grants, and default-deny SQL function permissions.
- **Data integrity:** PostgreSQL GiST exclusion constraints prevent overlapping time entries, while composite foreign keys enforce ownership boundaries.
- **Full-stack engineering:** Server Components, Server Actions, user-scoped timer persistence, and failed-save recovery workflows.
- **Testing & analytics:** Timezone-aware SQL reporting tested across daylight-saving transitions, with automated Vitest and pgTAP suites running in CI.

📚 **Documentation:** [Architecture](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/architecture.md) · [Database](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/database.md) · [Testing](https://github.com/raphael-antioquia/timemetrics/blob/main/docs/testing.md)

---

## 🛠️ Technical Skills

| Area | Technologies |
|---|---|
| **Languages** | Java, TypeScript, JavaScript, Ruby, SQL |
| **Backend** | Spring Boot, Ruby on Rails, Node.js, Express, REST APIs, JDBC |
| **Frontend** | React, Next.js, Tailwind CSS |
| **Databases** | PostgreSQL, Supabase, Flyway |
| **Testing** | JUnit, Testcontainers, Mockito, Vitest, pgTAP |
| **DevOps** | Docker, Docker Compose, GitHub Actions, GHCR, Linux, Caddy |
| **Observability** | Sentry, Micrometer, Spring Boot Actuator |

---

## 🤝 Connect

Open to backend and full-stack software development opportunities in Toronto/GTA and across Canada.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raphael-antioquia/)
