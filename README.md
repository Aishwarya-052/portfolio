# Aishwarya — Full-Stack Web Developer

Building end-to-end web applications with clean REST/GraphQL APIs, relational databases, and responsive React/Next.js interfaces.

[GitHub](https://github.com) • [LinkedIn](https://linkedin.com) • [Resume](./resume.pdf) • your.email@domain.com

---

## 🛠️ Full-Stack Tech Stack

* **Frontend:** React, Next.js (App Router), TypeScript, Tailwind CSS, HTML5/CSS3
* **Backend:** Node.js, Express, Python (FastAPI), REST APIs, WebSockets
* **Database & Cache:** PostgreSQL, Prisma ORM, MongoDB, Redis
* **DevOps & Tooling:** Git, Docker, Vercel, AWS (EC2/S3), Postman, Jest

---

## 🚀 Featured Web Applications

### 1. PayFlow — Collaborative Kanban & Event Sync
* **The Problem:** Remote teams struggled with state sync delays and clunky drag-and-drop interfaces across multiple boards.
* **The Architecture:** 
  * *Frontend:* Next.js client with optimistic UI updates and Tailwind CSS.
  * *Backend:* Node.js + Express server with Socket.io for sub-50ms event broadcasting.
  * *Database:* PostgreSQL normalized schema with Prisma transactions.
* **Key Metric:** Reduced UI latency to <30ms; supported 500+ concurrent WebSocket connections stress-tested via k6.
* [Live Demo](https://payflow-demo.com) | [Source Code](https://github.com/payflow)

### 2. SaaSBox — Multi-Tenant Billing Portal
* **The Problem:** Managing subscription tiers, usage metering, and invoice generation required patching three external tools.
* **The Architecture:**
  * *Frontend:* React + Vite dashboard with role-based access control (RBAC).
  * *Backend:* Python FastAPI handling webhook verification and usage aggregation cron jobs.
  * *Database:* MongoDB for flexible event logs + PostgreSQL for core user/billing state.
* **Key Metric:** Automated 100% of monthly billing cycles, cutting support tickets for invoice adjustments by 60%.
* [Live Demo](https://saasbox-demo.com) | [Source Code](https://github.com/saasbox)

---

## 💻 Full-Stack Architecture / System Design Snippet
*Want to see how I structure code? Check out:*
* [`/server`](./server) — Clean separation of controllers, services, and database repositories.
* [`/client/src/components`](./client/src/components) — Reusable, accessible UI primitives.
* [`/prisma/schema.prisma`](./prisma/schema.prisma) — Relational schema design with proper indexing.
# portfolio
Personal engineering portfolio, live demos, and technical case studies.
