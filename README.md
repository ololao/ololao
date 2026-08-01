<div align="center">

```
██████╗ ██╗      ██████╗ ██╗      █████╗  ██████╗ 
██╔═══██╗██║     ██╔═══██╗██║     ██╔══██╗██╔═══██╗
██║   ██║██║     ██║   ██║██║     ███████║██║   ██║
██║   ██║██║     ██║   ██║██║     ██╔══██╗██║   ██║
╚██████╔╝███████╗╚██████╔╝███████╗██║  ██║╚██████╔╝
 ╚═════╝ ╚══════╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝ ╚═════╝
```

### Backend Developer · Python · FastAPI · PostgreSQL

*Building robust APIs and reliable backend architectures*

</div>

---

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## ⚡ What I Do

- **Design and build REST APIs** with **Python** and **FastAPI** — from routing and dependency injection to layered architecture and error handling
- **Model and optimize relational databases** — **PostgreSQL** with deep knowledge of transactions, window functions, CTEs, indexes, and complex JOINs
- **ORM mastery** via **SQLAlchemy 2.0** — async sessions, relationships, bulk operations, hybrid properties, mixins, soft deletes
- **Cache and queue** with **Redis** — caching patterns, rate limiting, session management, API response caching
- **Containerize and ship** with **Docker** — optimized multi-stage builds, `uv`-powered images, Docker Compose stacks
- **Deploy** behind **Nginx** — reverse proxy, WebSocket support, load balancing, HTTPS, security hardening
- **Write async Python** from the ground up — `asyncio`, `Task`, `TaskGroup`, `gather`, `uvloop`, async context managers and generators

---

## 📚 Knowledge Base

<details>
<summary><b>🐍 Python Core</b></summary>
<br>

**Fundamentals & Standard Library**
- `datetime`, `os`, `sys`, `json`, `csv`, `pathlib`, `shutil`, `zipfile`
- `subprocess`, `argparse`, `re` (regular expressions)

**Advanced Python**
- Iterators, generators, `send()`/`throw()`, generator-based coroutines
- Decorators, closures, `nonlocal`, `functools` (`cache`, `lru_cache`, `partial`, `reduce`)
- `itertools` — `chain`, `groupby`, `islice`, `combinations`, `permutations`, `tee`, `zip_longest`
- `collections` — `namedtuple`, `defaultdict`, `OrderedDict`, `Counter`, `deque`
- Walrus operator `:=`, f-strings advanced formatting, `match/case`
- Recursion, heaps (`heapq`), stacks and queues

**OOP**
- Magic/dunder methods — full spectrum: `__new__`, `__del__`, `__repr__`, `__eq__`, `__hash__`, `__call__`, `__slots__`, and more
- Properties, `@classmethod`, `@staticmethod`, `@singledispatchmethod`
- Descriptors, context managers (`__enter__`/`__exit__`, `@contextmanager`, `contextlib`)
- Inheritance, `super()`, MRO, multiple inheritance
- Abstract classes (`abc`), polymorphism, composition, mixins
- `dataclasses`, `Enum`, bit operators
- Sequence, iterator, and context manager protocols

**Type System**
- Full type annotation syntax, `TypeVar`, `Generic`, `Protocol`, `Annotated`, `Literal`

**Ecosystem & Tooling**
- Virtual environments: `venv`, `poetry`, `uv`
- Module system, import internals, `__init__.py`
- Environment variables, `python-dotenv`

</details>

<details>
<summary><b>⚡ FastAPI & Backend</b></summary>
<br>

**FastAPI**
- Application architecture — layered structure (routers → services → repositories)
- Dependency injection system, `Depends`, scoped dependencies
- `APIRouter`, tags, response models, status codes
- Pydantic v2 — model design, validators, `model_config`, `Settings`
- CORS, Middleware, `lifespan` events
- Pagination, search, media file management
- `loguru` logging
- `gunicorn` + `uvicorn` production setup

**Authentication & Security**
- JWT access/refresh token flow
- Cookie-based sessions
- Authorization middleware

**Testing**
- `pytest` — fixtures, parametrize, conftest
- API testing with `httpx` / `TestClient`

**HTTP Protocol**
- Methods, status codes, headers, OPTIONS
- RESTful API design principles
- Request/response lifecycle

**Async**
- `asyncio` from scratch — event loop, coroutines, tasks, futures
- `Task`, `TaskGroup`, `gather`, `wait`, `as_completed`
- `asyncio.timeout`, `wait_for`
- `uvloop`, eager task factory
- Async context managers, async generators
- `contextvars`, `to_thread`, thread pool executors
- Sockets, `selectors`, callbacks, streams

**Integrations**
- YooKassa payment API

</details>

<details>
<summary><b>🗄️ Databases</b></summary>
<br>

**PostgreSQL**
- Data types, constraints, `NULL` semantics
- Full CRUD, `WHERE`, `ORDER BY`, `LIMIT/OFFSET`, `LIKE/ILIKE`, `IN`, `BETWEEN`
- JOINs — `INNER`, `LEFT`, `RIGHT`, `FULL`, `CROSS`
- Aggregate functions, `GROUP BY`, `HAVING`, `FILTER`
- Subqueries, CTEs, recursive CTEs
- Window functions — `ROW_NUMBER`, `RANK`, `LAG/LEAD`, `PARTITION BY`
- Transactions — isolation levels, `SAVEPOINT`, `SELECT FOR UPDATE/SHARE`
- Indexes — B-tree, partial, covering, `EXPLAIN ANALYZE`
- `ALTER TABLE`, `CAST`, `UPSERT`, `RETURNING`, `DISTINCT ON`

**SQLAlchemy 2.0**
- Engine, `connect()`, sync and async sessions
- Table definitions via ORM classes (`DeclarativeBase`)
- `relationship()` — `lazy`, `selectinload`, `joinedload`, `back_populates`
- Full query syntax — `select`, `insert`, `update`, `delete`
- `__table_args__`, `hybrid_property`, event system
- Bulk operations, soft delete pattern, mixins
- Pydantic ↔ SQLAlchemy integration (response models)

**Alembic**
- Migration generation and management

**Redis**
- All data types — strings, hashes, lists, sets, sorted sets, streams
- Transactions (`MULTI/EXEC`), `WATCH`
- Caching patterns — cache-aside, write-through, cache invalidation
- API response caching with FastAPI
- Rate limiting, session management, counters
- Redis testing strategies

</details>

<details>
<summary><b>🐋 DevOps & Infrastructure</b></summary>
<br>

**Docker**
- Image building, layer optimization, `.dockerignore`
- Multi-stage builds, `uv`-based modern Python images
- Docker Compose — services, volumes, networks, `depends_on`, health checks
- Container networking

**Nginx**
- Configuration structure, `server`/`location` blocks
- Static files, `try_files`, `proxy_pass`
- Reverse proxy for FastAPI/uvicorn
- WebSocket proxying, timeouts, custom headers
- Load balancing (`upstream`)
- HTTPS/TLS, security headers, performance tuning
- Nginx inside Docker

**Linux**
- Shell navigation, permissions (`chmod`, `chown`, `umask`), groups
- Process management (`ps`, `kill`, `jobs`, `nohup`)
- Redirections, pipes, filters (`grep`, `awk`, `sed`, `cut`, `sort`, `uniq`)
- Package management (`apt`)
- SSH — key setup, server configuration, `sftp`, `ftp`
- Networking (`ip`, `ss`, `netstat`, `curl`, `wget`)
- File search (`find`, `locate`), environment variables
- `vim`/`vi` editing

</details>

<details>
<summary><b>🌿 Git & Workflow</b></summary>
<br>

- Core Git — staging, commits, history, refs
- Branching strategies, Pull Requests
- `merge` vs `rebase` — when and why
- Conflict resolution
- `git stash`, `cherry-pick`, tags
- SSH key setup for GitHub
- **GitHub Actions** — CI/CD pipelines, workflow YAML, triggers, jobs

</details>
