# İzzet Ali Arslan

**Software engineer based in Istanbul, building toward data engineering.** I build products end to end: data model, pipelines, API, UI, tests, CI and deployment.

Most of my work sits where a real operational problem meets production concerns — access control, encryption, auditability, predictable AI costs, and deployments that someone else can run. I use AI where it earns its place in the product, and I keep a rule-based fallback for when it does not.

- 🏥 Currently delivering **BakımEvi**, a patient tracking and encrypted document management system sold to a care facility in Turkey
- 🧠 Interested in AI integrations that stay grounded in the user's own data
- 📊 Focusing on data engineering: Python data pipelines, SQL and PostgreSQL data modelling, dbt, orchestrated jobs — latest: [**El Clásico Analytics**](https://github.com/arslannizzetali/el-clasico-analytics)
- 📫 [arslannizzet10@gmail.com](mailto:arslannizzet10@gmail.com) · [LinkedIn](https://www.linkedin.com/in/izzetarslann/) · [X](https://x.com/arslanizzetali)

## Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**El Clásico Analytics**](https://github.com/arslannizzetali/el-clasico-analytics) · [live dashboard](https://arslannizzetali.github.io/el-clasico-analytics/) | Tactical analysis of 29 Real Madrid – Barcelona league matches (2005–2021) built from 3.1M StatsBomb events: idempotent incremental loads into a PostgreSQL event store, dbt models with tests, 16 data quality checks, bootstrap confidence intervals and an interactive static dashboard reproduced byte for byte in CI. | Python, PostgreSQL, dbt, Dagster, Parquet, GitHub Actions |
| [**BakımEvi**](https://github.com/arslannizzetali/bakim-merkezi) | Healthcare ERP for elderly and disability care facilities: patient tracking, role-based access, AES-256-GCM envelope-encrypted documents, audit log, retention jobs and per-facility multi-tenant deployment. Client project. | Next.js, Express, Prisma, PostgreSQL, Redis, MinIO, Docker |
| [**YouCanPark**](https://github.com/arslannizzetali/YouCanPark) | Product prototype for QR-based smart parking: scan in, scan out, pay for the exact time used, with an operator panel for pricing and capacity. | Next.js, TypeScript, Tailwind CSS |
| [**Tournament Management System**](https://github.com/arslannizzetali/turnuva-yonetim-sistemi) | Offline desktop app that runs football and volleyball tournaments: draw, fixtures, standings, knockout bracket, byes and forfeits. | Electron, JavaScript |

## Tech stack

**Frontend** — TypeScript, React, Next.js (App Router), Tailwind CSS, TanStack Query, Zustand

**Backend** — Node.js, Express, Prisma, Zod, JWT auth with refresh-token rotation, Bull queues

**Database & caching** — PostgreSQL, Redis

**DevOps & storage** — Docker, Docker Compose, Caddy, MinIO (S3-compatible), GitHub Actions, pnpm workspaces

**Data & AI** — Python data pipelines (ingestion, sampling, aggregation), SQL, dbt, Dagster, Parquet, data quality checks, Prisma migrations, Claude API (Anthropic SDK) with structured JSON outputs

**Testing & desktop** — Vitest, integration tests against real services, Electron

## How I work

- Business rules live in pure, tested functions; UI and transport stay thin
- Security decisions are written down, including the known gaps
- Every project repository has CI, an English README and a documented local setup
