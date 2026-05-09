
<h1 align="center">Hi, I'm Dzaky 👋</h1>

<p align="center">
  Backend · Infrastructure · Fullstack
</p>

<p align="center">
  Jakarta Metropolitan Area, Indonesia
</p>

<p align="center">
  <a href="mailto:dzakyalr@gmail.com">Email</a> ·
  <a href="https://dzaky.dev">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/dzakyalr">LinkedIn</a>
</p>



## About

I build backend systems, internal platforms, and production infrastructure for real-world business operations.

Mostly working with **TypeScript, Go, Node.js, PostgreSQL, Docker, Linux, GitHub Actions, cloud, VPS, and on-premise environments**.

I like practical engineering: clean APIs, reliable deployments, observability, backups, infrastructure that is simple enough to maintain, and systems that actually fit the business context.

---

## Focus

- Backend systems and service design
- Internal platforms and operational tools
- Production deployment workflows
- Cloud, VPS, and on-premise infrastructure
- Monitoring, health checks, logs, and backups
- Cost-aware architecture and practical reliability

---


## Things I Work On

```mermaid
flowchart LR
    A[Backend] --> B[APIs]
    A --> C[Business Logic]
    A --> D[Services]

    E[Frontend] --> E1[Web Apps]
    E --> E2[Mobile Apps]
    E --> E3[Desktop Apps]
    E --> E4[UI/UX Implementation]

    F[Infrastructure] --> G[Cloud]
    F --> H[VPS]
    F --> I[On-premise]

    J[Operations] --> K[Monitoring]
    J --> L[Backups]
    J --> M[Health Checks]

    N[Product] --> O[Dashboards]
    N --> P[Internal Tools]
    N --> Q[Workflows]
```

## My Go To Architecture

```mermaid
flowchart TD
    Dev[Developer Machine] --> Git[Git Repository]

    Git --> CI[CI Pipeline]

    CI --> Test[Run Unit & Integration Tests]
    Test --> Coverage[Generate Coverage Report]
    Coverage --> Sonar[SonarQube Analysis]

    Sonar --> Gate{Quality Gate Passed?}

    Gate -- No --> Block[Block Merge / Fix Code]
    Gate -- Yes --> Build[Build Docker Image]

    Build --> Registry[Container Registry]
    Registry --> Deploy[Deploy to Server]

    Deploy --> API[Go API]
    Deploy --> Worker[Go Workers]

    API --> Postgres[(PostgreSQL)]
    Worker --> Postgres
    API --> RabbitMQ[(RabbitMQ)]
    Worker --> RabbitMQ

    API --> Logs[Structured Logs]
    Worker --> Logs
    API --> Metrics[Metrics / Monitoring]
    Worker --> Metrics
```
## Connect

* Email: [dzakyalr@gmail.com](mailto:dzakyalr@gmail.com)x
* Portfolio: [Portfolio](https://dzaky.dev)
* LinkedIn: [LinkedIn](https://www.linkedin.com/in/dzakyalr)

```
```
