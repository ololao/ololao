<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&color=0:000000,50:1F2937,100:111111&text=doaks&fontSize=64&fontColor=38BDF8&fontAlignY=34&stroke=38BDF8&strokeWidth=0.4" width="100%" alt="doaks — python / backend / postgresql" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=880&height=46&lines=Backend+developer%3A+APIs+that+don't+fall+over;Python+%C2%B7+asyncio+%C2%B7+FastAPI+%C2%B7+PostgreSQL;SQLAlchemy+2.0+%C2%B7+Redis+%C2%B7+RabbitMQ;Docker+%C2%B7+Nginx+%C2%B7+Linux+%C2%B7+GitHub+Actions;%2F%2F+TODO%3A" alt="what i do" />

<p>
  <a href="https://github.com/doaks?tab=repositories"><img src="https://img.shields.io/badge/repositories-111111?style=for-the-badge&logo=github&logoColor=E6EDF3" alt="repositories" /></a>
  <a href="https://github.com/doaks?tab=followers"><img src="https://img.shields.io/github/followers/doaks?style=for-the-badge&label=followers&labelColor=111111&color=111111&logo=github&logoColor=38BDF8" alt="followers" /></a>
  <a href="https://t.me/"><img src="https://img.shields.io/badge/Telegram-111111?style=for-the-badge&logo=telegram&logoColor=2CA5E0" alt="Telegram" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:111111,100:38BDF8" width="90%" alt="" />

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=3776AB" />
  <img src="https://img.shields.io/badge/asyncio-111111?style=for-the-badge&logo=python&logoColor=FFD43B" />
  <img src="https://img.shields.io/badge/FastAPI-111111?style=for-the-badge&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/Pydantic%20v2-111111?style=for-the-badge&logo=pydantic&logoColor=E92063" />
  <img src="https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/SQLAlchemy%202.0-111111?style=for-the-badge&logo=sqlalchemy&logoColor=D71F00" />
</p>

<p>
  <img src="https://img.shields.io/badge/Redis-111111?style=for-the-badge&logo=redis&logoColor=FF4438" />
  <img src="https://img.shields.io/badge/RabbitMQ-111111?style=for-the-badge&logo=rabbitmq&logoColor=F6608F" />
  <img src="https://img.shields.io/badge/Pytest-111111?style=for-the-badge&logo=pytest&logoColor=0A9EDC" />
  <img src="https://img.shields.io/badge/Docker-111111?style=for-the-badge&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Nginx-111111?style=for-the-badge&logo=nginx&logoColor=009639" />
  <img src="https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=FCC624" />
</p>

<p>
  <img src="https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git&logoColor=F05032" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-111111?style=for-the-badge&logo=githubactions&logoColor=2088FF" />
  <img src="https://img.shields.io/badge/uv-111111?style=for-the-badge&logo=uv&logoColor=DE5FE9" />
  <img src="https://img.shields.io/badge/SQL-111111?style=for-the-badge&logo=postgresql&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-111111?style=for-the-badge&logo=jsonwebtokens&logoColor=D63AFF" />
  <img src="https://img.shields.io/badge/REST%20API-111111?style=for-the-badge&logo=openapiinitiative&logoColor=6BA539" />
</p>


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:111111,100:38BDF8" width="90%" alt="" />

## My stack

| | Технологии |
|:---|:---|
| **Язык** | Python · asyncio · typing |
| **Фреймворк** | FastAPI · Pydantic v2 · JWT |
| **Данные** | PostgreSQL · SQLAlchemy 2.0 · Atlas |
| **Кэш / очереди** | Redis · RabbitMQ (aio-pika) |
| **Инфраструктура** | Docker · Nginx · Linux |
| **Инструменты** | Git · GitHub Actions · pytest · uv |

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:111111,100:38BDF8" width="90%" alt="" />

## Details

</div>

|  Тема | Изученный материал |
|:---|:---|
| **Python** | ядро языка и модель памяти · stdlib (`datetime`, `pathlib`, `re`, `subprocess`, `json`, `zipfile`) · ООП: дуnder-методы, дескрипторы, MRO, `abc`, миксины, `dataclasses` · итераторы и генераторы (`send` / `throw`) · декораторы и замыкания · `functools` (`lru_cache`, `partial`) · `itertools` · `collections` · `match/case`, walrus · типизация: `TypeVar`, `Protocol`, `Annotated` · venv / poetry / uv, механика импортов |
| **Асинхронность** | event loop изнутри · корутины, `Task`, `Future` · `TaskGroup`, `gather`, `wait`, `as_completed` · таймауты (`wait_for`, `timeout`) · `uvloop`, eager task factory · async context managers и генераторы · `contextvars` · `to_thread` и пулы потоков · сокеты, `selectors`, callbacks, streams · `asyncio.Queue` / `Lock` |
| **FastAPI** | слоистая архитектура (routers → services → repositories) · dependency injection · `APIRouter` · Pydantic v2: валидаторы, `model_config`, Settings · аутентификация, JWT access/refresh, cookie-сессии · CORS, middleware, `lifespan` · обработка ошибок · пагинация и поиск · медиафайлы · WebSockets · `loguru` · gunicorn + uvicorn · интеграция YooKassa |
| **Безопасность** | OAuth 2.0 и OpenID Connect · JWT + refresh-токены · стратегии хранения сессий · OWASP: топ уязвимостей и защита · authorization middleware |
| **PostgreSQL** | типы данных и ограничения · полный CRUD, `LIKE`/`ILIKE`, `IN`, `BETWEEN` · JOIN всех видов · агрегаты, `GROUP BY` / `HAVING` / `FILTER` · подзапросы, CTE и рекурсивные CTE · оконные функции (`ROW_NUMBER`, `RANK`, `LAG`/`LEAD`) · транзакции: уровни изоляции, `SAVEPOINT`, `SELECT FOR UPDATE` · индексы: B-tree, partial, covering · `EXPLAIN ANALYZE` · `UPSERT`, `RETURNING`, `DISTINCT ON`, `CAST` |
| **SQLAlchemy 2.0** | Engine и async-сессии · `DeclarativeBase` · `relationship()`: `selectinload`, `joinedload`, `back_populates` · полный query syntax (select/insert/update/delete) · `__table_args__` · `hybrid_property` · система событий · bulk-операции · soft delete и миксины · интеграция с Pydantic · миграции Atlas |
| **Redis** | строки, хэши, списки, множества, sorted sets, streams · транзакции `MULTI/EXEC`, `WATCH` · паттерны cache-aside, write-through, инвалидация · кэширование ответов API · rate limiting, сессии, счётчики · стратегии тестирования Redis |
| **RabbitMQ** | базовая модель очередей · распределение задач между consumer'ами · временные очереди · dead letter exchanges · TTL сообщений · aio-pika: надёжная доставка, персистентность сообщений на диск |
| **Тестирование** | pytest: фикстуры, `parametrize`, `conftest`, маркеры · тестовая БД vs моки · `dependency_overrides` · async-тесты · FastAPI + httpx · testcontainers · faker · coverage (`cov`) |
| **Docker / Nginx** | Dockerfile и слои, `.dockerignore` · multi-stage builds + uv · compose: volumes, networks, health checks · сети контейнеров · Nginx: `location`, статика, `try_files` · reverse proxy для FastAPI · WebSockets, таймауты · балансировка `upstream` · HTTPS/TLS, security headers · Nginx в Docker |
| **Linux / Git** | shell и навигация · права (`chmod`, `chown`, `umask`) · процессы (`ps`, `kill`, `nohup`) · перенаправления и фильтры (`grep`, `awk`, `sed`) · SSH, sftp · сеть (`ip`, `ss`, `curl`) · vim · Git: ветвление, merge vs rebase, конфликты, `stash`, `cherry-pick`, теги · GitHub Actions CI/CD |
