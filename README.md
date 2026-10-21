# Thomas Wotoro

Computer Science student focused on **backend engineering and systems programming**. I build Python services and command-line tools, and I’m learning how software behaves closer to the operating system.

- **Backend:** Python, Flask, FastAPI, Django, REST APIs, PostgreSQL, SQLite
- **Systems:** C, Linux, Bash, processes and command execution
- **Engineering tools:** Git, GitHub Actions, Docker, Docker Compose

## Selected Projects

### [Sentinel Monitor](https://github.com/tomi3-11/sentinel-monitor)
A command-line monitor for website uptime and TLS certificate health.
- Runs concurrent HTTP checks and collects SSL certificate expiry information.
- Uses YAML configuration and reports individual-site failures without stopping the whole run.
- Includes pytest tests and GitHub Actions checks for linting and multiple Python versions.

**Stack:** Python, asyncio, httpx, sockets/TLS, YAML, pytest

### [Task Manager API](https://github.com/tomi3-11/taskmanager-redis-rl)
A REST API for task management, with authentication and supporting infrastructure.
- JWT access/refresh tokens, registration, password reset, and email flows.
- PostgreSQL persistence, Redis integration, rate limiting, and database migrations.
- Uses an application factory, API versioning, and OpenAPI/Swagger documentation.

**Stack:** Python, Flask, PostgreSQL, Redis, JWT, SQLAlchemy, Docker Compose

### [LAN Paste](https://github.com/tomi3-11/lan-paste)
A self-hosted paste service intended for a trusted LAN or private Tailscale network.
- Flask web interface and JSON/raw-body API backed by SQLite.
- Supports expiring pastes, a 1 MiB content limit, and token-protected deletion.
- Packaged with Docker Compose; CI runs tests, Python syntax checks, and a Docker image build.

**Stack:** Python, Flask, SQLite, Docker, pytest, GitHub Actions

### [ClubIQ](https://github.com/tomi3-11/ClubIQ)
A club-management platform for members, events, attendance, and related workflows.
- Flask REST API with a Next.js frontend and PostgreSQL.
- Uses Clerk for authentication and Docker Compose to run the application services.
- Includes backend linting and tests in GitHub Actions.

**Stack:** Python, Flask, Next.js, PostgreSQL, Clerk, Docker Compose

## Systems Programming

### [AC3 Shell](https://github.com/tomi3-11/ac3-SH3LL)
An early-stage C shell experiment. The current prototype reads a command, tokenizes arguments, launches a process with `fork` and `execvp`, and waits with `waitpid`. It is a learning project, not a full POSIX-compatible shell.

## Current Focus

- Designing and testing maintainable backend APIs
- Understanding Linux processes, system calls, and C
- Improving deployment workflows with containers and CI

## Contact

- [LinkedIn](https://www.linkedin.com/in/thomas-wotoro-a8504233a/)
- [Email](mailto:thomaswotoro@gmail.com)
