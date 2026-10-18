# Prajwal P Joshi

**Software Engineer · Full-Stack Development · Backend Systems · Cloud & Automation**

Bengaluru, India · [LinkedIn](https://www.linkedin.com/in/prajwal-joshi-a67460271/) · [Email](mailto:prajwaljoshi1856@gmail.com)
<!-- Portfolio link removed while https://prajwal-joshi.onrender.com is suspended on Render. Re-add once it is back online:
· [Portfolio](https://prajwal-joshi.onrender.com) -->

I build web applications and backend services with TypeScript, React, Next.js and Node.js. Much of my work sits between application code and the systems around it: APIs, databases and caching, automated tests, containers and CI, and finding out why a service is misbehaving.

## Engineering focus

- **Backend APIs:** Node.js, Express and Fastify services with input validation, authentication (JWT, OAuth) and role-based access control.
- **Data and caching:** PostgreSQL and Prisma, with Redis for caching, rate limiting and pub/sub.
- **Testing:** Playwright for end-to-end tests, Vitest for unit and integration tests, and Postman for exploring APIs.
- **Reliability and delivery:** health checks, retry/backoff, structured logging, Docker and GitHub Actions pipelines.

## Featured project: CacheForge

[Repository](https://github.com/Prajwalpjoshi/cacheforge) · [Live demo](https://cacheforge.netlify.app/)

A lab for measuring API performance with and without a cache. A small product-catalog API runs against a real PostgreSQL database and a real Redis instance, so you can watch the effect of caching on real requests rather than a simulation.

- Cache-aside reads with TTLs, plus explicit cache invalidation when data is written.
- A Redis-backed fixed-window rate limiter on write and benchmark endpoints, which returns `429` with `Retry-After`.
- Redis pub/sub events whenever a product is written.
- A metric record for every request, summarised as P50/P95/P99 latency, error rate and cache hit rate.
- A Performance Lab page that benchmarks database-only reads against cached reads.
- A health endpoint that reports PostgreSQL and Redis separately. If Redis is unavailable, reads fall back to PostgreSQL.
- Vitest unit and integration tests across the API, the web app and the shared packages.

**Stack:** Next.js, TypeScript, Tailwind CSS, Fastify, Zod, Pino, PostgreSQL, Prisma, Redis, Vitest, Docker Compose, pnpm workspaces

## Other public projects

- [ai-devops-security-assistant](https://github.com/Prajwalpjoshi/ai-devops-security-assistant): a MERN application that uses an LLM to analyse logs, scan for vulnerabilities and generate test cases. It has JWT and Google OAuth sign-in, Docker, and a GitHub Actions build.
- [playwright-ui-api-automation-framework](https://github.com/Prajwalpjoshi/playwright-ui-api-automation-framework): e-commerce UI and API tests built with Playwright, the Page Object Model and GitHub Actions.
- [selenium-python-file-automation](https://github.com/Prajwalpjoshi/selenium-python-file-automation): file upload and download tests built with Selenium, pytest and headless CI runs.

## Technical skills

| Area | Tools and practices |
|---|---|
| Languages | JavaScript, TypeScript, Python |
| Frontend | React, Next.js, Angular, Tailwind CSS |
| Backend | Node.js, Express, Fastify, REST APIs, WebSockets |
| Data | PostgreSQL, MySQL, MongoDB, Redis, Prisma |
| Testing | Playwright, Vitest, Postman, API and integration testing |
| DevOps and cloud | Linux/WSL, Git, Docker, Docker Compose, GitHub Actions, CI/CD, AWS fundamentals |
| Security and reliability | JWT, OAuth, RBAC, service health monitoring, retry/backoff, troubleshooting |
| Workflow | AI-assisted development |

## Currently learning

- **Distributed systems:** replication, message queues and event-driven design.
- **Redis beyond caching:** distributed rate limiting, queues and cache consistency.
- **AI developer tools:** agent workflows and practical automation for engineering teams.
- **Fundamentals:** data structures, algorithms and system design.

## Contact

I'm open to Software Engineer, Full-Stack, Backend and developer-tools roles.

[LinkedIn](https://www.linkedin.com/in/prajwal-joshi-a67460271/) · [Email](mailto:prajwaljoshi1856@gmail.com) · [GitHub](https://github.com/Prajwalpjoshi)
