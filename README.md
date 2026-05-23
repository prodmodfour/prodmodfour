# Ashraf Hussain

Backend/platform-focused software engineer based in Manchester, UK, with professional STFC experience.

I work across Python, APIs, data systems, Docker, CI/CD, observability and technical documentation. I am interested in backend, platform, cloud and SRE-adjacent engineering: systems that are maintainable, testable and understandable in production.

## What I work with

- **Backend:** Python, FastAPI, REST APIs, SQL, PostgreSQL, SQLAlchemy, Alembic, Pydantic
- **Platform:** Docker, Docker Compose, Redis, GitHub Actions, CI/CD, Linux
- **Reliability:** Prometheus, Grafana, structured logging, request IDs, health/readiness checks, runbooks
- **Infrastructure:** Terraform, AWS ECS/Fargate, RDS, CloudWatch
- **Engineering practice:** pytest, Ruff, mypy, Git, documentation, architecture decisions

## Featured backend/platform projects

### [carbon-platform-api](https://github.com/prodmodfour/carbon-platform-api)

Production-style FastAPI backend for compute-carbon reporting with PostgreSQL, Redis, Docker Compose, Prometheus/Grafana, structured JSON logging, request ID propagation, health/readiness checks, Alembic migrations, tests, CI, runbooks and deployment documentation.

**Shows:** API design, database modelling, observability, Dockerised local development, testing and operational documentation.

### [job-runner-platform](https://github.com/prodmodfour/job-runner-platform)

Worker-based background job platform with PostgreSQL as the durable source of truth, Redis dispatch signalling, worker leases, retries, idempotency, cooperative cancellation, dead-letter handling, Prometheus metrics, structured logs, runbooks and CI.

**Shows:** async backend design, reliability thinking, failure handling, worker lifecycle management and operational trade-offs.

### [multi-tenant-saas-api](https://github.com/prodmodfour/multi-tenant-saas-api)

SaaS-style FastAPI backend demonstrating organisations as tenants, authentication, RBAC, API keys, audit logging, idempotency, PostgreSQL migrations, Docker Compose, Prometheus/Grafana and quality gates.

**Shows:** commercial backend patterns, tenant isolation, auth/authorisation boundaries, security-conscious API design and maintainable service structure.

### [platform-infra-lab](https://github.com/prodmodfour/platform-infra-lab)

AWS/Terraform platform lab modelling ECS/Fargate services behind an ALB, private RDS PostgreSQL, optional Redis, IAM role boundaries, Secrets Manager references, CloudWatch observability, rollback docs, security notes and validation-only CI.

**Shows:** platform engineering awareness, infrastructure-as-code, deployment boundaries, cloud architecture and safe operational design.

## Technical community

I founded and chair [STFC Early Careers Code Club](https://stfc-early-careers-code-club.github.io/), a weekly technical talk and discussion group for early-career staff.

I lead a committee of four, coordinate speakers, facilitate discussion and maintain the public site/contribution workflow.

## Current focus

- Backend and platform engineering
- Production-style Python APIs
- Reliable worker systems
- Observability, CI/CD and runbooks
- Cloud/platform infrastructure design

## Contact

- GitHub: [github.com/prodmodfour](https://github.com/prodmodfour)
- Email: [prodmodfour@gmail.com](mailto:prodmodfour@gmail.com)

## Passion projects and experiments

Alongside my backend/platform portfolio, I also maintain personal projects that reflect my broader engineering interests: long-lived tools, typed domain modelling, local-first workflows, CLI design, protocol boundaries and product-shaped software.

### [rotom-table](https://github.com/prodmodfour/rotom-table)

Long-running Nuxt 3 / TypeScript tabletop companion for Pokémon Tabletop United campaigns. It brings together an isometric map table, editable Pokémon and trainer sheets, encounter-table tooling, a searchable Pokédex, reference pages and filesystem-backed campaign data.

**Shows:** long-term ownership, TypeScript/Nuxt application structure, complex Vue UI, local-first persistence, domain modelling, interactive map tooling, testing and refactoring discipline.

### [missive](https://github.com/prodmodfour/missive)

Early-stage Rust command-line tool and local control plane for A2A-native agent communication. The project explores agent messaging, task/context management, routing, collectives, local adapters, gateway behaviour, SQLite-backed state and structured CLI output.

**Shows:** Rust systems development, CLI design, protocol-aware architecture, workspace organisation, typed domain modelling, local service design, testing discipline and interest in agent/tooling infrastructure.
