<h1 align="center">Hi, I'm Maciej Zieliński 👋</h1>

<p align="center">
  <b>Junior Python backend developer</b> · 4th-year Computer Science student at PJATK (Programming &amp; Robotics) · Warsaw, Poland
</p>

<p align="center">
  <a href="https://maciejzielinski.dev/"><img alt="Open my portfolio" height="52" src="https://img.shields.io/badge/Portfolio-open_my_site-2EA043?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/maciej-zieli%C5%84ski-28669b3a4/"><img alt="LinkedIn" height="52" src="https://img.shields.io/badge/LinkedIn-connect_with_me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

I build practical software in Python — REST APIs and backend systems, data pipelines, and applied AI / computer vision. I care about clean architecture, tests, and projects that solve a real problem.

## 🛠️ Tech stack

<p>
  <img alt="Tech stack" src="https://skillicons.dev/icons?i=python,fastapi,django,flask,postgres,sqlite,docker,linux,git,githubactions,java,ts,svelte,opencv&perline=14">
</p>

| Area | Tools |
|---|---|
| **Backend** | Python (strongest), FastAPI, Django REST Framework, Flask, SQLAlchemy, Alembic, asyncio, background jobs |
| **Data & AI** | SQL / PostgreSQL, Qdrant, pandas, RAG pipelines, OpenCV, MediaPipe |
| **Tooling** | Docker, Git, GitHub Actions, Linux (Ubuntu daily), pytest (incl. plugins), PyPI publishing, Render / Cloudflare Pages |
| **Also** | Java (JMS, Servlets), TypeScript, Svelte, Kotlin (Android) |

## 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[pytest-queryguard](https://github.com/MaciejZiel/pytest-queryguard)** | pytest plugin that catches N+1 queries, enforces query budgets and finds missing PostgreSQL indexes for SQLAlchemy 2 (sync, async and FastAPI `TestClient`), pointing to the offending line and suggesting the fix (`selectinload`, `CREATE INDEX`). On [PyPI](https://pypi.org/project/pytest-queryguard/): stable [0.3.0](https://github.com/MaciejZiel/pytest-queryguard/releases/tag/v0.3.0), 0.4 release candidates in progress | Python · pytest · SQLAlchemy · PostgreSQL · asyncpg · PyPI |
| **[gtfs-rt-kit](https://github.com/MaciejZiel/gtfs-rt-kit)** | Typed Python client and toolkit for GTFS-Realtime feeds (vehicle positions, trip updates, alerts) and static GTFS: sync and async clients with retries, vehicle matching and delays, CLI. On [PyPI](https://pypi.org/project/gtfs-rt-kit/) with [docs](https://maciejziel.github.io/gtfs-rt-kit/) | Python · httpx · protobuf · mypy strict · PyPI |
| **[pgqueue](https://github.com/MaciejZiel/pgqueue)** | Background job queue that runs only on PostgreSQL: `SKIP LOCKED` claiming, retries with backoff, leases with crash recovery, LISTEN/NOTIFY wake-ups, cron, dashboard and Prometheus metrics. ~6,600 jobs/s with 8 workers and ~4 ms pickup latency on a laptop | Python · asyncpg · PostgreSQL · FastAPI |
| **[CaseFlow](https://github.com/MaciejZiel/caseflow)** | Multi-tenant backend for case &amp; document workflows: tenant isolation, RBAC, versioned uploads, review flows, audit log, signed webhooks and retryable background work, with a Next.js workspace | FastAPI · PostgreSQL · Next.js · Docker |
| **[Motorsport API](https://github.com/MaciejZiel/Motorsport_API)** | REST API for a fictional championship with computed standings, cookie- or token-based JWT auth and OpenAPI docs, plus a new Angular dashboard on top | Django REST · PostgreSQL · Angular |
| **[Agentic RAG Platform](https://github.com/MaciejZiel/agentic-rag-platform)** | Upload documents and get answers with source citations: background indexing on a worker, tenant-scoped retrieval, TOTP 2FA, structured extraction to JSON | FastAPI · PostgreSQL · Qdrant · Celery · React |
| **[Procurement Graph](https://github.com/MaciejZiel/procurement-graph)** | Traces Polish public procurement from buyer to supplier on 1,214 real BZP notices, with SQL analytics, a relationship map and PL/EN UI | FastAPI · PostgreSQL · React |
| **[Live Flights Map](https://github.com/MaciejZiel/live_flights_map)** | Self-hosted live air-traffic map from public ADS-B feeds, with flight and airport details and replay from a local archive | Flask · SQLite · Svelte · Leaflet |
| **[firm-radar](https://github.com/MaciejZiel/firm-radar)** | Profile of a Polish company from official public registries (KRS, VAT white list, BZP procurement), stored as snapshots so it shows what changed and when. JSON API plus a PL/EN web UI | FastAPI · PostgreSQL · SQLAlchemy · htmx |
| **[plan-bot](https://github.com/MaciejZiel/plan-bot)** | Telegram and Discord bot for university timetables from ICS feeds: next class, reminders and change alerts, DST-safe recurrence | Python · aiohttp · discord.py · SQLAlchemy |

<p>
  <a href="https://github.com/MaciejZiel/Motorsport_API"><img src="https://raw.githubusercontent.com/MaciejZiel/Motorsport_API/master/docs/screenshots/standings.png" alt="Motorsport API: championship standings in the Angular dashboard" width="49%"></a>
  <a href="https://github.com/MaciejZiel/caseflow"><img src="https://raw.githubusercontent.com/MaciejZiel/caseflow/master/docs/images/dashboard.png" alt="CaseFlow: case list in the Next.js workspace" width="49%"></a>
</p>

Also: **[Reroute](https://github.com/MaciejZiel/Reroute)**, a local-first Warsaw transit control room with live vehicle positions, line punctuality and rerouting around closures (FastAPI · PostGIS · React · MapLibre).

<sub>More in <a href="https://github.com/MaciejZiel?tab=repositories">repositories</a> and on my <a href="https://maciejzielinski.dev/">portfolio</a>.</sub>

## 🤝 Open source

- **[sqlalchemy-utils #838](https://github.com/kvesteri/sqlalchemy-utils/pull/838)**: fixed the Read the Docs build so autodoc can import the package (merged).

## 🌱 Currently

- Writing my engineering thesis on real-time motion tracking with computer vision
- Building a personal inflation tracker that reads shopping receipts on the phone (on-device OCR, PWA)
- Looking for a **junior backend / Python developer** role or internship in Warsaw or remote

## 📫 Contact

✉️ zielinski.macio@gmail.com · [LinkedIn](https://www.linkedin.com/in/maciej-zieli%C5%84ski-28669b3a4/) · [Portfolio](https://maciejzielinski.dev/)
