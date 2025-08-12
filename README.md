
- # Backend
Backend service for handling match data, event logging, and live updates via APIs.

## To-Dos:
- Banele: setup CD -> that needs decision on what hosting platform  
- Connect our repo on that deployment site  
- Add deploy step in some workflow so that every time GitHub Actions gets hit we check the code -> deploy automatically if passed  
- (Use separate staging and prod envs if possible)? # not necessary, imposes good convention  
- ESLint and Prettier so to keep code clean  
- Add these configs to both front and back  
- In CI  

---

## CHATGPT RUNDOWN for DevOps

### Phase 1 – Project Foundation  
We want to set up repos, permissions, branches, and team workflows.

- GitHub Organizations & Permissions (roles, owners, members)  
- Git & GitHub basics (branching, pull requests, merges)  
- Branch protection rules & GitHub settings  
- Docker basics (containers, images, docker-compose) — for local dev environments  
- Jira basics or any Agile ticketing tool (boards, issues, sprints)  
- Environment variables & `.env` files  

---

### Phase 2 – Automation & CI/CD  
We want automated testing, builds, and deployments.

- GitHub Actions fundamentals (workflows, jobs, triggers)  
- Basic CI pipelines (linting, testing, building)  
- CD pipelines & deployment automation (to platforms like Netlify, Render)  
- ESLint & Prettier (code style and formatting tools)  
- Husky & Git hooks (pre-commit checks)  
- Unit testing frameworks (Jest for backend, Vitest or Jest for frontend)  

---

### Phase 3 – Infrastructure & Observability  
We want repeatable setups, error tracking, and schema versioning.

- Advanced Docker & docker-compose (multi-container apps)  
- Basic infrastructure as code (IaC) concepts (Terraform/Kubernetes basics — optional for now)  
- Logging libraries in Node.js (Winston, Pino)  
- Error tracking services (Sentry setup and usage)  
- Database migrations (Prisma or Laravel migrations)  
- Basic monitoring concepts (logs, metrics, alerts)  

---

### Phase 4 – Documentation & Handover  
We want clear docs and production readiness.

- Markdown documentation best practices  
- API documentation standards (Swagger/OpenAPI basics)  
- Architecture diagramming tools (draw.io, Lucidchart)  
- Hosting platforms: Netlify, Vercel, Render, Railway (deployment guides)  
- Backup strategies for databases (cron jobs, provider backups)  

