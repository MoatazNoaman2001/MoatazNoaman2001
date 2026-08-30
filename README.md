# Moataz Noaman

Backend and fullstack engineer in Cairo. I build the operational systems businesses
actually run on: accounting and inventory, CRM, ERP dashboards, review workflows,
care platforms. Two years and eight months of remote production work.

Most of it comes back to the data layer — transactions that hold up, permissions
enforced in the database rather than the interface, and audit trails that still make
sense six months later.

[moataz.noaman12@gmail.com](mailto:moataz.noaman12@gmail.com) ·
[LinkedIn](https://linkedin.com/in/moataz-noaman-02196222a) ·
[Résumé](https://flowcv.com/resume/m7a5j1n7ui) ·
[WhatsApp](https://wa.me/201098518194)

**Open to remote backend, fullstack and mobile roles, and to freelance work. Available immediately.**

---

## Experience

| Role | Company | Stack | Period |
|:-----|:--------|:------|:-------|
| Full-Stack Developer | Red Software Development | Node.js, TypeScript, Next.js, Flutter, PostgreSQL (Cloud SQL), Google Cloud | May 2026 – Aug 2026 |
| Fullstack Engineer | LibraryInfoSpace, India | Express, TypeScript, PostgreSQL, Redis, BullMQ, Socket.IO, React | Sep 2025 – Apr 2026 |
| Backend Engineer | Al-vora, Portugal | Java, Quarkus, Timefold Solver, PostgreSQL, Redis, gRPC, Docker | Jul 2025 – Mar 2026 |
| Fullstack Developer | Otomatika | Node.js, MongoDB, Meta Ads API, Google Ads API, OpenAI | 2025, 2 months |
| Teaching Assistant | Zewail University | Computer Networks, Network Programming | Feb – Jun 2024 |

---

## Selected work

### [Orphan Data Observatory](https://goco.orphans.care) · live
`Laravel` `PostgreSQL` `Blade` `RBAC`

A bilingual Arabic and English platform publishing orphan-care indicators for 166
countries. No figure goes public without its source, its year and a confidence grade
from A to E, and where no acceptable number exists the gap is published as a declared
gap rather than left blank. Partner organisations submit figures that move through a
seven-stage review with four roles, per-item decisions and an append-only audit log.
Around 1,400 published figures in production.

### [Al-Haj Salim — Steel & Cement Accounting](https://al-haj-salim-steel-cement-accountin.vercel.app/dashboard) · live
`Next.js` `TypeScript` `Supabase` `PWA`

An accounting and inventory system for a distributor who was running everything on
spreadsheets. A single sale has to post to inventory, the customer ledger, the driver
account and the bank book together or not at all, so that lives in 52 Postgres
functions rather than application code. 79 row-level-security policies enforce access
in the database, including hiding profit from cashiers. Nothing is ever edited or
deleted — corrections are linked entries and the original stays visible. Works offline
and replays writes on reconnect. Entirely in Arabic, right to left.

### EasyDo CRM · work project
`Express` `TypeScript` `PostgreSQL` `Redis` `BullMQ`

A multi-tenant WhatsApp Business CRM. I joined an early-stage codebase as the main
backend developer and grew it to 37 Postgres tables and around 217 REST endpoints.
Campaign queue on Redis and BullMQ with per-message delivery tracking, RSA-encrypted
WhatsApp Flows, HMAC webhook verification, and a Gemini assistant answering from each
tenant's own uploaded documents with their keys encrypted at rest.

### Itqan — Odoo 18 Analytics Dashboards · freelance
`Python` `Odoo 18` `OWL` `Chart.js` `PostgreSQL`

Five dashboards for a retail group covering inventory, car sales, fashion, finance and
HR, written as native OWL components rather than bought as a dashboard module. Stock is
valued from Odoo's real valuation layers instead of the cost field, which is usually
stale, and the finance figures were reconciled line by line against the client's own
accountant.

### [Sprint Skills — PMP Certification Platform](https://pmp.skill-sprint.com/) · live
`Laravel 12` `PostgreSQL` `Blade` · [source](https://github.com/MoatazNoaman2001/exam_system)

An exam platform serving 100+ users, with 200+ questions across 12 PMP knowledge
domains, a scoring engine, attempt history and session management.

### [Gold E-Commerce](https://gold-frontend-pi.vercel.app/) · ITI graduation project
`Node.js` `Express` `MongoDB` `Socket.IO` · [source](https://github.com/MoatazNoaman2001/Gold-Backend)

A platform for buying and reverse-selling gold, with three roles and real-time chat
between sellers and buyers over Socket.IO with message persistence.

### Optimisation work
`Java` `Genetic Algorithm` `Tabu Search` `Simulated Annealing`

[CVRP Route Optimization](https://github.com/MoatazNoaman2001/cvrp) — a capacitated
vehicle routing solver using metaheuristics, parallelised with ExecutorService and
CompletableFuture. [UAV Route Optimization](https://github.com/MoatazNoaman2001/UAV-Route-Optemization) —
drone supply delivery for urban areas. The same interest turned up at work: the
scheduling engine at Al-vora runs on a constraint solver over more than two hundred
properties per solve.

### [Vitalism](https://github.com/MoatazNoaman2001/ncnn_Android_mediapipe_blazeface_rppg) · BSc graduation project
`Android` `C++` `OpenCV` `NCNN` `MediaPipe`

Non-invasive measurement of heart rate, SpO2 and blood pressure from a phone camera
using rPPG, with on-device inference through a JNI C++ bridge. Open source.

### Also
**Laikji** — Flutter chat rooms and live streaming over WebRTC and MediaSoup, published
on Google Play, with the Node.js WebSocket server behind it.
**[Wessol Backend](https://github.com/MoatazNoaman2001/wessol_back)** — Spring Boot 3
REST API with Redis caching and JPA Specifications.
**Real Estate Management** — Flutter Desktop app for property listings, contracts and
financial tracking.

---

## Tech

**Node.js** — Express, TypeScript, TypeORM, Prisma, Mongoose, BullMQ and Redis queues,
Socket.IO, server-sent events, JWT and OAuth 2.0, WebAuthn, OpenAPI, Jest, Vitest.
Learning NestJS.

**Java** — Quarkus in production; Spring Boot, Spring Security and Spring Data JPA on my
own projects. Hibernate/JPA, Timefold Solver, gRPC, Maven, JUnit 5, Mockito.

**PHP and Python** — Laravel with Eloquent, Blade, middleware, policies and gates, queues
and jobs, events and listeners, Sanctum. Odoo 18 module development in Python, and Django.

**Frontend** — React, Next.js (App Router, Server Components), Angular, Vue, TypeScript,
Tailwind, Redux Toolkit, TanStack Query, PWA, i18n and RTL.

**Mobile** — Flutter and Dart in production: BLoC, Drift and SQLite, offline-first sync,
hardware-backed secure storage, Codemagic. Native Android in Kotlin with MVVM, Retrofit,
Room, Coroutines and Hilt.

**Data** — PostgreSQL (transactions, stored procedures, row-level security), MySQL,
MongoDB, Redis, Supabase, Firebase, SQLite, PowerSync.

**Delivery** — Docker and Docker Compose, GitHub Actions, CI/CD, Nginx, Linux, Bash,
Vercel, Railway, Google Cloud, Prometheus metrics. AWS, Kubernetes and Terraform from the
DEPI DevOps programme rather than production. Claude Code in daily use.

---

## Education

| Programme | Institution | Year |
|:----------|:------------|:-----|
| Open-Source Track, 9 months | Information Technology Institute (ITI) | Oct 2024 – Jul 2025 |
| DevOps Engineering | Digital Egypt Pioneer Program (DEPI) | 2024 |
| BSc Bioinformatics, GPA 3.43 | Assiut University | 2019 – 2023 |
