# Hi, I'm Maciej Zieliński

[![PyPI](https://img.shields.io/pypi/v/pytest-queryguard?label=pytest-queryguard&logo=pypi&logoColor=white)](https://pypi.org/project/pytest-queryguard/)

## About

I'm a junior Python backend developer and a fourth-year Computer Science student at PJATK in Warsaw. I mostly write Python: REST APIs and backend systems, data pipelines and some applied AI. I like clean architecture and tests, and I prefer projects that solve a real problem.

**Looking for a junior backend / Python developer role or internship in Warsaw or remote.**

<img src="https://skillicons.dev/icons?i=py,fastapi,postgres,docker,ts,react,svelte,git,linux&perline=9" alt="Technologies I use: Python, FastAPI, PostgreSQL, Docker, TypeScript, React, Svelte, Git and Linux" height="40">

## Projects

| Project | What it is | Links |
| :-- | :-- | :-- |
| **pytest-queryguard** | pytest plugin that fails tests hiding N+1 queries and missing indexes in SQLAlchemy 2 code. On PyPI (stable 0.3.0, 0.4 release candidates in progress). | [Source](https://github.com/MaciejZiel/pytest-queryguard) · [PyPI](https://pypi.org/project/pytest-queryguard/) |
| **Contrail** | Self-hosted real-time flight tracker with a WebGL map, a photo per aircraft, the full track and the route ahead. | [Try it live](https://contrail.maciejzielinski.dev) · [Source](https://github.com/MaciejZiel/contrail) |
| **Reroute** | Live Warsaw transit map with delays, plus a LightGBM model that predicts arrival delays (about 9% lower error than a persistence baseline on held-out data). | [Try it live](https://reroute.maciejzielinski.dev) · [Source](https://github.com/MaciejZiel/Reroute) |
| **CaseFlow** | Multi-tenant FastAPI backend for case and document workflows with RBAC, audit log and signed webhooks, and a Next.js frontend. Public read-only demo. | [Try it live](https://caseflow.maciejzielinski.dev) · [Source](https://github.com/MaciejZiel/caseflow) |
| **clip_to_text** | Local video-to-text transcription with queued jobs, live progress and SRT export. | [Source](https://github.com/MaciejZiel/clip_to_text) |
| **pgqueue** | Background job queue on PostgreSQL (`SKIP LOCKED`, leases, retries, dashboard). | [Try it live](https://pgqueue.maciejzielinski.dev) · [Source](https://github.com/MaciejZiel/pgqueue) |
| **Gravity Studio** | Interactive Solar System viewer: a Pygame desktop app and a Three.js browser version, with orbital elements from JPL and textures from Solar System Scope. | [Try it live](https://gravity.maciejzielinski.dev) |
| **plan-bot** | Telegram and Discord bot for university timetables from ICS feeds. | [Source](https://github.com/MaciejZiel/plan-bot) |

Self-hosted demos: [System status](https://status.maciejzielinski.dev)

## Open source

Merged:

- [cleder/awesome-python-testing #135](https://github.com/cleder/awesome-python-testing/pull/135): added pytest-queryguard to the Tools list.
- [sqlalchemy-utils #838](https://github.com/kvesteri/sqlalchemy-utils/pull/838): fixed the Read the Docs build so autodoc can import the package.

Open:

- [pytest #15164](https://github.com/pytest-dev/pytest/pull/15164): make `Pytester.syspathinsert()` affect subprocesses.
- [pytest-xdist #1397](https://github.com/pytest-dev/pytest-xdist/issues/1397): reported the `is_xdist_controller()` problem and proposed the fix; the maintainer's [PR #1398](https://github.com/pytest-dev/pytest-xdist/pull/1398) follows it.
- [awesome-sqlalchemy #85](https://github.com/dahlia/awesome-sqlalchemy/pull/85): add pytest-queryguard to the Testing section.

Also a [Stack Overflow answer](https://stackoverflow.com/a/80009289) on mapping a PostgreSQL view without a primary key in the SQLAlchemy ORM.

## Contact

[Portfolio](https://maciejzielinski.dev/) · [LinkedIn](https://www.linkedin.com/in/maciej-zieli%C5%84ski-28669b3a4/) · zielinski.macio@gmail.com
