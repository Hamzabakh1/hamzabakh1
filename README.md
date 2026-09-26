<div align="center">
  <img src="./hamzabakh.png" alt="Hamza Bakh — Data Engineering, Analytics and BI" width="100%" />

  <h1>Hamza Bakh</h1>
  <h3>Data Engineer · Analytics Engineer · BI & Data Infrastructure</h3>

  <p>
    I design reliable data platforms that turn operational data into governed models,<br />
    trusted metrics and decision-ready analytics.
  </p>

  <p>
    <a href="https://www.linkedin.com/in/hamza-bakh/"><img src="https://img.shields.io/badge/LinkedIn-Hamza%20Bakh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/Hamzabakh1?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Selected%20Work-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" /></a>
    <img src="https://img.shields.io/badge/Agadir-Morocco-0E7490?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Agadir, Morocco" />
  </p>

  <p><strong>Open to data engineering, analytics engineering, BI and data-platform opportunities.</strong></p>
</div>

---

## What I deliver

| Data platforms | Analytics products | Data reliability | Infrastructure operations |
|---|---|---|---|
| Batch and event ingestion, ETL/ELT orchestration, layered lakehouse and warehouse design | Dimensional models, semantic metrics, Power BI and Metabase decision products | Data contracts, validation, reconciliation, lineage and quality observability | PostgreSQL and SQL Server labs, monitoring, recovery, identity and secure messaging controls |

My work follows one operating principle: **a pipeline is not complete until its data is trusted, its failures are observable, and its output supports a real decision.**

## Engineering architecture

```mermaid
flowchart LR
    S[Operational sources<br/>APIs · files · databases] --> I[Ingestion & orchestration]
    I --> B[Bronze<br/>immutable landing]
    B --> Q[Quality & reconciliation]
    Q --> M[Silver / Core<br/>governed models]
    M --> G[Gold<br/>business marts]
    G --> BI[Semantic layer & BI]
    BI --> D[Business decisions]

    SEC[Identity & security] -. controls .-> I
    OBS[Monitoring & recovery] -. protects .-> Q
    OBS -. protects .-> M
```

## Selected work

| Project | Business and engineering outcome | Evidence |
|---|---|---|
| [Automated Validation Framework](https://github.com/Hamzabakh1/python-automated-validation-framework) | Reusable Python controls for schema, completeness, uniqueness and reconciliation checks | Executable validation modules and repeatable checks |
| [Multi-Tenant Data Warehouse](https://github.com/Hamzabakh1/multi-tenant-data-warehouse-saas-bi) | Tenant-isolated ingestion, warehouse modeling and embedded BI architecture | Data architecture case study |
| [ETL + Metabase Analytics](https://github.com/Hamzabakh1/PRJ_ETL_METABASE_PFE1) | Delivers a Python ETL workflow and analytics-ready tables for operational reporting | Implemented transformations and Metabase delivery structure |
| [Finora Financial Intelligence](https://github.com/Hamzabakh1/finora-financial-intelligence) | Finance-oriented platform blueprint with regional policy packs and executive analytics | Product and system architecture case study |
| [IRON CORE OS](https://github.com/Hamzabakh1/iron-core-os) | Connects projects, tasks, skills, KPIs and work sessions in a local-first execution system | Working application prototype and linked operating model |
| [Courtline](https://github.com/Hamzabakh1/courtline-padel-community) | Mobile-first padel matchmaking and community experience | Interactive front-end prototype |

## Private enterprise labs

These focused environments are maintained privately because they model administrative and infrastructure controls. Architecture, code walkthroughs and redacted execution evidence are available during technical discussions.

- **Enterprise Data & Infrastructure Lab** — identity decisions, data-quality gates, PostgreSQL, safe messaging, Prometheus monitoring, analytics controls and disaster recovery.
- **Azure Real Estate Data Platform** — Azure Data Factory orchestration, Bronze/Silver/Gold contracts, Azure SQL marts and Power BI delivery.
- **SQL Server Performance Clinic** — Query Store, workload baselining, targeted indexes, blocking diagnostics and before/after evidence.
- **PostgreSQL HA & PITR Lab** — replication design, WAL archiving, backup verification and point-in-time recovery procedures.
- **Database Infrastructure Observability** — exporters, Prometheus, Alertmanager, Grafana dashboards and controlled failure drills.
- **Identity Lifecycle Automation** — deterministic joiner/mover/leaver plans, access convergence, protected offboarding and audit trails.
- **Active Directory & Secure Mail Labs** — directory topology, policy validation, mail authentication, transport controls and incident runbooks.

## Technical toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=111827" alt="Power BI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
</p>

| Discipline | Tools and methods |
|---|---|
| Data engineering | Python, SQL, Azure Data Factory, ETL/ELT, APIs, orchestration and Docker |
| Analytics engineering | Dimensional modeling, dbt-style transformations, tests, documentation and semantic layers |
| Data architecture | Bronze/Silver/Gold, warehouse and lakehouse patterns, contracts, lineage and governance |
| BI engineering | Power BI, DAX, Power Query, Metabase, KPI design and finance analytics |
| Database reliability | PostgreSQL, SQL Server, Query Store, backup/recovery, performance and observability |
| Automation and controls | PowerShell, lifecycle workflows, CI, configuration validation and runbooks |

## How I work

1. Start with the user, operational problem and measurable acceptance criteria.
2. Define source contracts, ownership and security boundaries before implementation.
3. Keep raw, cleaned, core and consumption layers explicit.
4. Build quality, reconciliation and observability into the delivery path.
5. Test failure and recovery—not only the happy path.
6. Separate implemented capabilities from simulated or planned extensions.

## Current direction

- Production-grade data engineering and analytics engineering.
- Azure, SQL, orchestration, dimensional modeling and semantic governance.
- Database reliability, data observability and recoverable infrastructure.
- Clear technical communication for business, BI and platform stakeholders.

## Contact

- [LinkedIn — Hamza Bakh](https://www.linkedin.com/in/hamza-bakh/)
- [GitHub — Hamzabakh1](https://github.com/Hamzabakh1)
- Agadir, Morocco · Open to remote, hybrid, relocation and international opportunities

<div align="center">
  <strong>Reliable data · Clear decisions · Recoverable systems</strong>
</div>
