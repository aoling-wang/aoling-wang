# Kevin Wang

**Full stack developer, backend-leaning. Previously six years as an EMT in the FDNY 911 system.**

Emergency medicine is decision-making under uncertainty — incomplete information, a running clock, consequences for being wrong. It turns out that transfers to software more directly than I expected. I build things for people who are tired, distracted, or having a bad day, because that describes most users most of the time.

📍 New York metro · Open to full stack and backend roles at early-stage startups
📧 aoling.wang@gmail.com · [LinkedIn](https://www.linkedin.com/in/kevin-wang-dev/)

---

## What I'm building

### [Nature's Medicine API](https://github.com/aoling-wang) · `NestJS` `PostgreSQL` `Docker` `TypeORM`
A containerized REST API centralizing data on medicinal herbs worldwide.

- 10 endpoints, with authentication guards restricting `POST` / `PUT` / `PATCH` / `DELETE` while `GET` stays public
- 14 unit and integration tests covering database health and endpoint validation
- GitHub Actions workflow running the full suite on every push to `main`
- Docker Compose orchestrating the API and Postgres containers
- TypeORM repositories instead of raw SQL, for readability and injection safety

### [Sisyphus](https://github.com/aoling-wang) · `React Native` `Expo` `TypeScript` `MMKV`
A task manager for neurodivergent users.

Most task apps assume that once you've written a task down, you can start it. For a lot of people, that assumption is exactly where everything falls apart. Sisyphus is built around the three failure points research actually identifies: initiation, continuation, completion.

- Visual hierarchy, color psychology, and saturation used deliberately to pull attention toward the single next actionable item
- Local-first storage with MMKV — no account, no network dependency
- 10 reusable components with derived state for fast filtering and re-renders

### [Authenticator Microservice](https://github.com/aoling-wang) · `Python` `FastAPI` `SQLAlchemy` `SQLite`
A modular auth layer designed to drop into other projects instead of being rebuilt each time.

- bcrypt hashing with salting before any storage
- SQLAlchemy ORM to eliminate raw query surface area
- Pydantic request/response schemas validating credential format at the boundary
- Containerized, with relational tables for user and credential data

### [Error Alert Microservice](https://github.com/aoling-wang) · `Python` `HTTPX` `re`
A lightweight notification layer, built because I wanted to know when things broke without watching logs.

- Regex parsing to filter `ERROR` and `CRITICAL` log lines
- Formatted alerts delivered to Discord via webhooks
- Deployable as an independent service alongside any application

---

## Stack

**Languages** — TypeScript, JavaScript, Python, SQL
**Frontend** — React, React Native, Next.js, Expo, Tailwind CSS, HTML5, CSS3
**Backend** — Node.js, Express, NestJS, FastAPI
**Data** — PostgreSQL, SQLite, TypeORM, SQLAlchemy
**Infra & tooling** — Docker, Docker Compose, GitHub Actions, Git, Figma

---

## Before this

Six years as an EMT — Northwell Health and the FDNY 911 system, plus volunteer work on Long Island. I led critical calls in under-resourced communities with limited equipment and incomplete patient history, and spent a lot of time explaining complicated things to frightened people in plain language.

Before that, Boston College (B.S. Biology, 2019), where I wrote Python scrapers in a bacterial genomics lab to pull gene annotation data from half a dozen databases. That was 2017. It took me a while to notice it was the most interesting thing I'd done.

---

## Currently

Finishing the Scrimba Fullstack Developer Path, shipping projects, and looking for a team to join. If you're building something and need someone who'll take ownership of real surface area, I'd like to talk.

📧 aoling.wang@gmail.com