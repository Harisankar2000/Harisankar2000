<h1 align="center">Hi 👋, I'm Harisankar Sahoo</h1>
<h3 align="center">Backend Engineer · Node.js · JavaScript · TypeScript · PostgreSQL · Kafka · AWS</h3>

<p align="center">
  <a href="https://linkedin.com/in/harisankar-sahoo"><img src="https://img.shields.io/badge/LinkedIn-harisankar--sahoo-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:harisankarsahoo58@gmail.com"><img src="https://img.shields.io/badge/Email-harisankarsahoo58%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=harisankar2000&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

I'm a backend engineer with **4+ years** of experience building scalable, secure Node.js services across **fintech, EV fleet management, healthcare/pharma and edtech**. I like problems where correctness matters: real-time data pipelines, money movement and systems that must not lose an event.

- 🔭 **Now:** Software Engineer at **TapFin** (Mumbai), building the backend for an EV fleet-finance platform: real-time telemetry, lender risk analytics, loan origination and notifications
- 🧱 **Day to day:** Node.js (JavaScript) microservices on Fastify, PostgreSQL & ClickHouse, Kafka & BullMQ pipelines, Redis, Docker and Jenkins CI/CD
- 🌱 **Exploring:** distributed systems patterns: transactional outbox, idempotency, workflow orchestration
- 💬 **Ask me about:** event-driven architecture, double-entry ledgers, Kafka, PostgreSQL concurrency
- 📫 **Reach me:** [LinkedIn](https://linkedin.com/in/harisankar-sahoo) or harisankarsahoo58@gmail.com

---

### 🚀 Featured project

#### [🏦 NeoBank: digital banking platform](https://github.com/Harisankar2000/neobank)

<p>
  <a href="https://neobank-harisankar.vercel.app"><img src="https://img.shields.io/badge/Live_demo-neobank--harisankar.vercel.app-4F46E5?logo=vercel&logoColor=white" alt="Live demo" /></a>
  <a href="https://github.com/Harisankar2000/neobank"><img src="https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white" alt="Source code" /></a>
  <a href="https://github.com/Harisankar2000/neobank/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/Release-v1.0.0-2EA44F" alt="Release v1.0.0" /></a>
</p>

Simulated **digital bank** with a customer app and an admin console: accounts, transfers, beneficiaries, daily limits, CSV/PDF statements and notifications. Staff review risky transfers, post reversals, freeze accounts and run **reconciliation**.

- **Double-entry ledger:** every money movement posts balanced debit and credit entries; PostgreSQL triggers reject unbalanced or edited journal entries
- **Safe transfers:** atomic, concurrency-safe (ordered row locks, deadlock retries) and **idempotent** (Idempotency-Key stored in the same transaction), proven by tests: 50 parallel transfers against one balance, exactly 10 succeed
- **Fraud controls:** daily limits and risk rules (large amount, new beneficiary, Redis velocity counter) hold money in a suspense account until an admin approves
- **Events:** **transactional outbox → Kafka** with an idempotent consumer, so no event is lost or processed twice
- **Deployed:** React on Vercel, API on Render, Postgres on Neon, Redis on Upstash

Try it: log in as `harisankar@neobank.dev` / `NeoBank@2026`; the admin console is at `/admin`.

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
</p>

---

### 💼 Experience

| Role | Company | Highlights |
| --- | --- | --- |
| **Software Engineer** · Nov 2024 – Present | TapFin (Tapsys Pvt Ltd) | Real-time EV fleet telemetry & analytics APIs (ClickHouse, PostgreSQL), Kafka & BullMQ pipelines, lender risk dashboards, loan origination workflows, Better Auth with RBAC, multi-channel notification service |
| **Jr. Backend Engineer** · Aug 2023 – Oct 2024 | Sirovate Technologies | Clinical Study Report generation platform with multi-stage review workflows on AWS Lambda, S3 and PostgreSQL |
| **Jr. Backend Developer** · Jun 2022 – Jul 2023 | TimesPro (Times Group) | Unified login system with AWS Cognito, Lambda, API Gateway and MongoDB |

---

### 🛠️ Tech stack

**Languages**
<br/><img src="https://skillicons.dev/icons?i=js,ts,python" />

**Backend & APIs:** Node.js · Fastify · Express · REST · GraphQL · WebSockets
<br/><img src="https://skillicons.dev/icons?i=nodejs,express,graphql,fastapi" />

**Data & messaging:** PostgreSQL · ClickHouse · MongoDB · Redis · Kafka · BullMQ · Prisma
<br/><img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,kafka,prisma" />

**Cloud & DevOps:** AWS (Lambda, S3, EC2, API Gateway, Cognito, SNS) · Docker · Jenkins · GitHub Actions
<br/><img src="https://skillicons.dev/icons?i=aws,docker,jenkins,githubactions,linux,git" />

**Frontend & testing:** React · Tailwind CSS · Vitest · Jest · Postman
<br/><img src="https://skillicons.dev/icons?i=react,tailwind,vite,jest,postman" />

---

### 📊 GitHub stats

<p>
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Harisankar2000&theme=default" alt="GitHub stats" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Harisankar2000&theme=default" alt="Top languages" />
</p>
<p>
  <img src="https://streak-stats.demolab.com?user=Harisankar2000&hide_border=true" alt="Contribution streak" />
</p>
