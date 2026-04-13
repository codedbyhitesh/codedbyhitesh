<h1 align="center">
  Hi, I'm Hitesh Mishra 👋
</h1>

<h3 align="center">
  .NET Backend Engineer · Clean Architecture · AI-Integrated Systems
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/mishra-hitesh-a40800210/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://portfolio-showcase--w172mishra.replit.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white" />
</p>

---

## About Me

I'm a backend-focused software engineer working primarily in the **.NET / C# ecosystem**, with a focus on building systems that are structured, maintainable, and designed to scale. I gravitate toward clean layered architecture — separating concerns deliberately across controllers, services, repositories, and data models.

My recent work spans enterprise workflow systems, AI-integrated platforms, and financial management tools. I pay attention to things like audit trails, role-based access control, real-time communication with SignalR, containerization with Docker, and CI/CD pipelines on Azure.

I'm not just writing code — I'm thinking about how the pieces connect, how data flows through a system, and how it will behave under real usage conditions.

---

## Tech Stack

**Languages**
- C#, TypeScript, JavaScript, SQL

**Backend / Frameworks**
- ASP.NET Core MVC, ASP.NET Core Web API, Entity Framework Core, SignalR

**Databases**
- PostgreSQL, SQL Server, EF Core Migrations

**Architecture & Patterns**
- Repository Pattern, Dependency Injection, Service Layer Pattern, Clean Layered Architecture, RBAC

**DevOps & Cloud**
- Docker, Docker Compose, GitHub Actions (CI/CD), Azure Container Registry, Azure Web App for Containers

**Frontend (supporting)**
- Bootstrap 5, jQuery / AJAX, Chart.js, Kendo Grid

**AI / Integrations**
- OpenAI API integration, AI-assisted financial analysis pipelines

---

## Featured Projects

### 🔷 CaseNexus — Case Investigation Management System
> **Stack:** ASP.NET Core MVC (.NET 8) · PostgreSQL · SignalR · Docker · GitHub Actions · Azure

An enterprise-inspired investigation and compliance platform. Built with a clear MVC + Repository + Service layer architecture. Key capabilities include multi-stage case workflows (Open → InReview → Resolved → Closed), a complete audit trail on every action, SLA breach detection, role-based access control (Admin / Investigator / User), real-time SignalR notifications, document evidence management, and a Chart.js analytics dashboard.

The project is fully containerised with Docker Compose and ships with a CI/CD pipeline that builds, pushes to Azure Container Registry, and deploys to Azure Web App for Containers on every push to `main`.

**What this demonstrates:** Layered backend design · Azure deployment pipeline · Real-time backend events · Compliance-grade audit logic

🔗 [View Repository](https://github.com/codedbyhitesh/CaseInvestigationManagementSystem)

---

### 🔷 Smart Employee Management System
> **Stack:** ASP.NET Core MVC (.NET 8) · C# · EF Core · AI Integration

An employee lifecycle management platform with AI-assisted features. Covers standard HR workflows with an intelligent layer on top for insights and automation.

**What this demonstrates:** AI integration within a .NET backend · Domain modeling for HR systems · Clean controller/service separation

🔗 [View Repository](https://github.com/codedbyhitesh/Smart-Employee-Management-System)

---

### 🔷 AI-Powered Finance Management Platform
> **Stack:** TypeScript · AI/LLM API Integration

A financial advisor platform that analyses user income and expense patterns and surfaces AI-driven insights. Built with a TypeScript backend and integrates with AI APIs to generate personalised financial commentary.

**What this demonstrates:** AI API integration · Financial domain modelling · TypeScript backend development

🔗 [View Repository](https://github.com/codedbyhitesh/ai-powered-Finance-Management)

---

### 🔷 YT Growth Strategist
> **Stack:** TypeScript · AI Integration

An AI-powered tool for YouTube channel growth strategy — analyses content niches, identifies audience patterns, and generates data-backed recommendations for creators.

**What this demonstrates:** AI-assisted content intelligence · Prompt engineering in production · TypeScript application design

🔗 [View Repository](https://github.com/codedbyhitesh/YT-Growth-Strategist)

---

## How I Approach Architecture

When I start a system, I think about **separation of concerns first**. My .NET projects follow a deliberate layering strategy:

```
Presentation (Controllers / Views)
        ↓
  Service Layer  ←  Business Logic lives here
        ↓
 Repository Layer  ←  Data access is isolated here
        ↓
    Database (EF Core / PostgreSQL)
```

This isn't academic — it's practical. When you separate cleanly:
- Services can be unit tested without touching the database
- Repositories can be swapped without touching business logic
- Controllers stay thin and readable

For cross-cutting concerns (auth, audit, logging), I implement them as middleware or decorators rather than scattering them through business logic.

---

## How I Approach Problems

- **Start with the data model.** Before writing a controller, I sketch out the entities and relationships. Bad schemas produce bad systems.
- **Audit and observability are features, not afterthoughts.** Systems that track "what changed and who changed it" are dramatically easier to debug and operate.
- **Containerise early.** Every project I build runs in Docker locally. This removes environment drift and simplifies deployment.
- **Automate the deployment path.** A feature that's difficult to ship is a feature that will accumulate bugs. CI/CD is a first-class concern.
- **Keep AI practical.** I integrate AI where it adds real value — financial insights, content analysis, employee recommendations — not as a decoration.

---

## GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=codedbyhitesh&theme=github_dark" width="100%" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=codedbyhitesh&theme=github_dark" height="150" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=codedbyhitesh&theme=github_dark" height="150" />
</p>

---

## Currently Working On

- Deepening .NET Web API skills (minimal APIs, versioning, middleware pipelines)
- Exploring Clean Architecture and CQRS patterns in .NET
- Building production-grade CI/CD pipelines on Azure

---

## Contact

- 💼 [LinkedIn](https://www.linkedin.com/in/mishra-hitesh-a40800210/)
- 🌐 [Portfolio](https://portfolio-showcase--w172mishra.replit.app/)
- 📁 [GitHub](https://github.com/codedbyhitesh)

*Open to backend engineering roles — .NET, API development, enterprise systems, SaaS platforms, and FinTech.*

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=codedbyhitesh&color=0078D4&style=flat&label=Profile+Views" />
</p>
