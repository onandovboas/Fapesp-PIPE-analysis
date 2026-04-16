# FAPESP PIPE Grants Analysis — SUPERA Innovation Park

## Business Problem

SUPERA Innovation Park (Ribeirão Preto, SP) needed to understand its position within the São Paulo state innovation ecosystem. The core question was: **why does the Ribeirão Preto metro region account for only 7% of all FAPESP PIPE grants in the state, and what strategic actions could increase that share?**

This analysis was delivered as a technical assessment for SUPERA's data and innovation team.

---

## What I Did

- Collected and structured **5,197 grants and subsidies** from FAPESP's public dataset, covering 1,949 distinct companies
- Built a **relational data model in Excel Power Query**, connecting grants, companies, institutions, research areas, municipalities, and metro regions into a single analytical layer
- Designed an **interactive Excel dashboard** for managers to filter and explore the data without technical knowledge
- Compared Ribeirão Preto's profile against São Paulo and Campinas — the two largest innovation hubs in the state
- Identified knowledge area gaps and proposed a strategic hypothesis for expanding the region's grant capture

---

## Key Findings

| Region | Share of PIPE Grants |
|---|---|
| São Paulo Metro | 38% |
| Campinas | 17% |
| Araraquara | 15% |
| Vale do Paraíba | 8% |
| **Ribeirão Preto** | **7%** |
| Piracicaba | 6% |

**Ribeirão Preto's knowledge profile** is concentrated in Agrarian Sciences (24%), Health Sciences (23%), and Biological Sciences (17%) — areas aligned with the region's agricultural and biomedical vocation.

**São Paulo and Campinas**, in contrast, are dominated by Engineering (36–38%) and Computer Science — areas with higher grant density and stronger links to deep tech entrepreneurship.

**Strategic hypothesis:** by establishing intentional relationships with local higher education institutions in Engineering and Computer Science, SUPERA could diversify the regional innovation profile and increase PIPE grant capture over a 2–3 year horizon.

---

## Proposed Next Steps (delivered to the team)

1. **KPI construction** — define a trackable metric for grant capture per outreach touchpoint
2. **Institution mapping** — identify Engineering and CS programs in the Ribeirão Preto metro area
3. **Monitoring routine** — establish a quarterly data review cycle to track progress

---

## Data Model

The analysis uses a relational model built in Excel Power Query, connecting the following entities:

- `Researcher` — individual grant recipients
- `Higher Education Institution` — linked to researchers and projects
- `Research Project` — core unit of analysis, with area, modality, and timeline
- `FAPESP Grant` — financial instrument linked to projects

See the full entity-relationship diagram below:

![Entity-Relationship Diagram](diagrama_entidade_relacionamento.pdf)

A more detailed relational schema — originally designed for a startup ecosystem mapping platform built during the same period — is also included to illustrate data modeling applied to a broader innovation context:

![Relational Diagram](diagrama_relacional.pdf)

---

## Files in This Repository

| File | Description |
|---|---|
| `fapesp_dashboard.xlsx` | Excel workbook with Power Query data model and interactive dashboard |
| `diagrama_entidade_relacionamento.png` | ER diagram of the FAPESP grants data model |
| `diagrama_relacional.png` | Full relational schema of the startup ecosystem mapping platform |
| `apresentacao_supera.pdf` | Final presentation delivered to the SUPERA team |

---

## Tools Used

- Excel (Power Query, Power Pivot, interactive dashboard)
- Data modeling (entity-relationship and relational diagrams)
- Exploratory data analysis
- Business storytelling and executive presentation

---

## Context

This project was developed as part of a technical assessment for **SUPERA Innovation Park** (Ribeirão Preto, SP), a technology park linked to the University of São Paulo. The dataset is based on publicly available FAPESP grant data.

---

*Fernando Vilas Boas Borges — [LinkedIn](https://www.linkedin.com/in/fernandovilasboas) · [GitHub](https://github.com/onandovboas)*
