# Hi, I'm Maciej Zieliński

Junior Python backend developer and 4th-year Computer Science student at PJATK in Warsaw. I build practical software in Python: REST APIs and backend systems, data pipelines, and applied AI. I care about clean architecture, tests, and projects that solve a real problem.

[Portfolio](https://maciejzielinski.dev/) · [LinkedIn](https://www.linkedin.com/in/maciej-zieli%C5%84ski-28669b3a4/) · zielinski.macio@gmail.com

## Projects

1. **[pytest-queryguard](https://github.com/MaciejZiel/pytest-queryguard)**: pytest plugin that fails tests hiding N+1 queries and missing indexes in SQLAlchemy 2 code. On [PyPI](https://pypi.org/project/pytest-queryguard/) (stable 0.3.0, 0.4 release candidates in progress).
2. **[Contrail](https://github.com/MaciejZiel/contrail)**: self-hosted real-time flight tracker with a WebGL map, a photo per aircraft, the full track and the route ahead. [Try it live](https://contrail.maciejzielinski.dev)
3. **[Reroute](https://github.com/MaciejZiel/Reroute)**: live Warsaw transit with delays; collects GTFS-Realtime data in PostgreSQL/PostGIS for an upcoming delay-prediction model. [Try it live](https://reroute.maciejzielinski.dev)
4. **[CaseFlow](https://github.com/MaciejZiel/caseflow)**: multi-tenant FastAPI backend for case and document workflows with RBAC, audit log and signed webhooks.
5. **[clip_to_text](https://github.com/MaciejZiel/clip_to_text)**: local video-to-text transcription with queued jobs, live progress and SRT export.
6. **[pgqueue](https://github.com/MaciejZiel/pgqueue)**: background job queue on PostgreSQL (`SKIP LOCKED`, leases, retries, dashboard). [Try it live](https://pgqueue.maciejzielinski.dev)
7. **[plan-bot](https://github.com/MaciejZiel/plan-bot)**: Telegram and Discord bot for university timetables from ICS feeds.

Self-hosted demos: [System status](https://status.maciejzielinski.dev)

## Open-source contributions

Merged:

- [cleder/awesome-python-testing #135](https://github.com/cleder/awesome-python-testing/pull/135): added pytest-queryguard to the Tools list.
- [sqlalchemy-utils #838](https://github.com/kvesteri/sqlalchemy-utils/pull/838): fixed the Read the Docs build so autodoc can import the package.

Open:

- [pytest #15164](https://github.com/pytest-dev/pytest/pull/15164): make `Pytester.syspathinsert()` affect subprocesses.
- [pytest-xdist #1397](https://github.com/pytest-dev/pytest-xdist/issues/1397): reported the `is_xdist_controller()` problem and proposed the fix; the maintainer's [PR #1398](https://github.com/pytest-dev/pytest-xdist/pull/1398) follows it.
- [awesome-sqlalchemy #85](https://github.com/dahlia/awesome-sqlalchemy/pull/85): add pytest-queryguard to the Testing section.

Also a [Stack Overflow answer](https://stackoverflow.com/a/80009289) on mapping a PostgreSQL view without a primary key in the SQLAlchemy ORM.

Looking for a junior backend / Python developer role or internship in Warsaw or remote.
