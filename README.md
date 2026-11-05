<h1>Eduardo Haas</h1>

**Senior Analytics Engineer · Data Engineer** — Santa Cruz do Sul, Brazil · open to remote

Business Administration graduate turned data engineer. I build production data platforms end to end — ingestion, layered modeling with dbt, business rules, BI and AI agents that sit on top of the data layer — for 30+ companies across 10+ industries, from hospitals to construction firms.

Mostly self-taught: I learned most of my stack by solving real client problems, which is why I care more about the right answer than the fanciest one.

`8+ years with production data` · `150+ data sources integrated` · `200+ dashboards shipped` · `600+ business users`

---

### How I build data platforms

```mermaid
flowchart LR
    A[ERPs · APIs · spreadsheets<br/>PostgreSQL · MySQL] -->|Python ETL/ELT · n8n| B[(BigQuery)]
    subgraph dbt
      B --> C[raw] --> D[staging] --> E[marts]
    end
    E --> F[Power BI dashboards]
    E --> G[Next.js data apps]
    E --> H[AI agents via MCP]
```

- **Modeling & business rules** — management P&L for a hospital, multi-company cost allocation, KPI layers that finance teams actually trust.
- **Data apps** — 15+ custom apps (Next.js, Supabase) where operations feed the warehouse directly: fleet logs, WhatsApp integrations, KPI portals.
- **AI on the data layer** — agents that draft commercial proposals and an MCP server that lets Claude query and act on company operations.

### Stack

![BigQuery](https://img.shields.io/badge/BigQuery-0b6e5f?style=flat-square&logo=googlebigquery&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-0b6e5f?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-0b6e5f?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-0b6e5f?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-0b6e5f?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-0b6e5f?style=flat-square&logo=n8n&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-0b6e5f?style=flat-square&logo=googlecloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0b6e5f?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-0b6e5f?style=flat-square&logo=supabase&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-0b6e5f?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0b6e5f?style=flat-square&logo=typescript&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20·%20MCP-0b6e5f?style=flat-square&logo=anthropic&logoColor=white)

### Projects

- [**management-pnl-dbt**](https://github.com/eduardohaas/management-pnl-dbt) — Management P&L for a group of companies: shared-cost allocation, inflation-adjusted results (Central Bank API), dbt layers, unit tests and CI with live docs.
- [**HTML_For_PowerBI**](https://github.com/eduardohaas/HTML_For_PowerBI) — HTML & CSS snippets to build custom visuals inside Power BI through DAX measures.

Most of my day-to-day work lives in private client repositories.

### Certifications

- **Anthropic Academy** — Building with the Claude API · Claude Code in Action · Model Context Protocol · Agent Skills (2026)
- **Data Science Academy** — Data Warehouse Design · Data Lake Design & Integration · Big Data Analytics · ML & AI in Distributed Environments (2023–24)

### Get in touch

[LinkedIn](https://www.linkedin.com/in/eduardo-haas-ab784b127/) · [eduardo@datenconsultoria.com.br](mailto:eduardo@datenconsultoria.com.br) · Portuguese (native) · English (B2)
