# Hi, I'm Dhruv Patel 👋

**Full-Stack Software Engineer** — backend, cloud, and developer tooling. Based in Toronto, ON 🇨🇦

I build production-grade applications: distributed microservices, cloud-native services, and open-source developer tools. Computer Programming & Data Analytics graduate (Seneca College, 2026), comfortable shipping across TypeScript, Java, and Python in Docker/Linux environments.

🔗 [Portfolio](https://dhruv-techdev.vercel.app) · [LinkedIn](https://www.linkedin.com/in/dhruv-patel-20b959288) · 📫 dhruv153908@gmail.com

---

## 🛠️ Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white)

**Databases & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## 🚀 Projects

### [ShopSphere — Microservices E-Commerce Backend](https://github.com/dhruv-techdev/ShopSphere-Microservices-E-Commerce)
`Java 21` · `Spring Boot 3` · `Spring Cloud` · `Kafka` · `PostgreSQL` · `Redis` · `Docker` · `Kubernetes`

An 8-service production-grade e-commerce backend (Gateway, User, Product, Cart, Order, Inventory, Payment, Notification) with Eureka service discovery, a centralized API Gateway, and a Kafka async event pipeline for order workflows. Schema-per-service DB isolation, JWT RBAC, Redis-backed cart, and OpenAPI 3 specs per service. Delivered 32 Jira user stories across multiple sprints with full GitFlow and CI gates. → [Docs](https://shopsphere-portfolio.vercel.app)

### [Fragments — Cloud-Native Microservice](https://github.com/dhruv-techdev/fragments-public)
`Node.js` · `Express 5` · `AWS S3 + DynamoDB + Cognito` · `GitHub Actions → ECR → ECS`

A REST microservice that stores, retrieves, and converts text/image fragments (Markdown→HTML, PNG→WebP). Dual-environment design — in-memory for dev, S3+DynamoDB for prod — switchable via env vars with zero code changes. Full CI/CD pipeline to AWS ECS, owner-isolated data access, 16 unit test files + 14 Hurl integration tests, and graceful shutdown handling. → [Live Demo](https://fragments-public.vercel.app/)

### VibeCart — Full-Stack E-Commerce Platform
`TypeScript` · `Express` · `Prisma (20+ models)` · `PostgreSQL` · `React 19` · `Vite 5` · `Tailwind 4` · `JWT`

A production e-commerce monorepo (apps/api, apps/web, packages/shared-types) with complete auth (JWT + refresh tokens, email verification, password reset), product catalog, cart, checkout, and an admin dashboard with RBAC. Audit logging, Sentry error tracking, Pino structured logging, and a standardized API response format across all endpoints. → [Live Demo](https://vibecart-staging.vercel.app/)

### [AI Job Search Assistant](https://ai-job-search-assistant.vercel.app/)
`Node.js 20+` · `TypeScript` · `Commander.js` · `OpenRouter` · `Tavily API` · `Zod`

A multi-stage CLI pipeline that reads job-posting PDFs and your resume, then uses LLMs to generate market analysis, skill-gap reports, and a 0–100 readiness score. Built a 4-stage AI pipeline with Zod schema validation on every LLM output, exponential-backoff multi-model fallback, and tiered Markdown action plans — keeping all sensitive data local. → [Live Demo](https://ai-job-search-assistant.vercel.app/)

### [React 19 Migration Safety Net](https://react19-migration-safety-net.vercel.app/)
`TypeScript 5.9` · `Node.js 20+` · `AST parsing` · `Jest (101+ tests)` · `npm workspaces`

A static-analysis CLI that scans React 16/17/18 codebases for deprecated APIs and unsafe patterns, outputting a 0–100 readiness score with precise file/line/column locations. 25+ detection rules with a weighted risk-scoring algorithm and a 4-package modular architecture (analyzer, runtime, reporter, CLI) integrating with GitHub Actions, GitLab CI, and Jenkins. → [Live Demo](https://react19-migration-safety-net.vercel.app/)

### [RSC Storybook Bridge](https://rsc-storybook-bridge-demo-app.vercel.app/)
`TypeScript 5.4` · `React 18+` · `Storybook 8` · `Vite 5` · `Vitest` · `MSW` · `PNPM workspaces`

An open-source monorepo library that bridges React Server Components into Storybook via server-data injection, rendering modes (server/client/hybrid), and boundary adapters — solving a real gap in modern React tooling. Includes deterministic rendering controls, per-story MSW mocking, version compatibility checks, and a CI helper with structured diagnostics. → [Live Demo](https://rsc-storybook-bridge-demo-app.vercel.app/)

### [SSE Streaming Reliability Kit](https://sse-streaming-reliability-kit.vercel.app/)
`TypeScript` · `Node.js 18+` · `Fastify 4` · `Vitest` · `AJV` · `Prometheus`

A production-ready Server-Sent Events toolkit with a zero-dependency client: auto-reconnect (exponential backoff + jitter), resume-from-last-event, deduplication, and liveness detection. State-machine connection lifecycle, Prometheus-compatible metrics, correlation IDs for distributed tracing, and a fault-injection harness with pre-built failure scenarios. → [Live Demo](https://sse-streaming-reliability-kit.vercel.app/)

---

## 💼 Freelance Work

### [Inventory Dashboard — Shopify Embedded App](https://github.com/dhruv-techdev/inventory-dashboard)
`TypeScript` · `React` · `React Router v7` · `Shopify App Bridge` · `Admin GraphQL API` · `Prisma` · `Docker`

A Shopify embedded app for inventory/product management. Integrated Shopify Admin GraphQL mutations to create products and bulk-update variants, configured app-level permissions (products, metaobjects, metafields), and implemented Prisma-backed OAuth session storage with uninstall/scope-update webhook handlers.

### [SyncFlow — Shopify Embedded App](https://github.com/dhruv-techdev/sync-flow)
`TypeScript` · `React` · `React Router v7` · `Shopify App Bridge` · `Admin GraphQL API` · `Prisma` · `Docker`

A Shopify embedded app for merchant workflow/data synchronization. Set up authenticated admin routes with Shopify OAuth and App Bridge, implemented app lifecycle webhooks (uninstall, scope updates), and managed deployment, access scopes, and embedded behavior through the Shopify CLI.

---

## 📜 Certifications

- **IBM Full Stack Software Developer** — IBM (2025)
- **Google Cloud Database Engineer** — Google Cloud (2024)
- **Google IT Support** — Google (2024)

---

⭐️ Open to junior / new-grad software engineering roles. Feel free to reach out!
