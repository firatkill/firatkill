# Fırat Kıl

Full-stack developer in Ankara, Türkiye. I build AI-powered SaaS products end to end, from the data model and auth to billing, background jobs, tests and deployment. Mostly Next.js, TypeScript and PostgreSQL.

Since September 2025 I've been a full-stack developer at Vizio AI, an AI product studio, where I lead or solely build client products: a legal research assistant with cited answers, a recruiting platform, an AI customer-support suite, the backend of a live auction marketplace and an HVAC takeoff and quoting tool. That work lives in private client repositories; [firatkil.com](https://firatkil.com) describes it in more detail.

## What I work with

- **Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS, TanStack Query
- **Backend:** Node.js, NestJS, REST, SSE, WebSockets, Spring Boot
- **Data:** PostgreSQL and Supabase (row-level security, SQL functions), pgvector, Redis, MongoDB
- **AI:** OpenAI, Gemini, Vercel AI SDK, retrieval-augmented generation, streaming chat, text-to-speech
- **Shipping:** Stripe, BullMQ, Docker, Vercel, Azure, GitHub Actions, Playwright, Vitest, pgTAP

## Public projects

| Project | What it is | Stack |
| --- | --- | --- |
| [ymm-invoice-app](https://github.com/firatkill/ymm-invoice-app) | Bulk e-invoice processing: upload a ZIP and BullMQ workers parse each invoice and report live progress | Next.js, BullMQ, Redis, Prisma |
| [devlink-app](https://github.com/firatkill/devlink-app) | REST API for developer link pages with JWT security; I recorded the build on YouTube | Java 17, Spring Boot, PostgreSQL |
| [latest-portfolio](https://github.com/firatkill/latest-portfolio) | The source of firatkil.com | Next.js |

## How I work

I write most code with AI coding agents. I still own the data model, the security rules and the tests, and I read every change before it ships. I like putting rules where they can't be skipped: row-level security in the database, payment state changed only by verified webhooks, concurrency-sensitive logic inside Postgres functions.

## Contact

[firatkil.com](https://firatkil.com) · [LinkedIn](https://linkedin.com/in/firatkill) · firatkill.is@gmail.com
