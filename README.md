# Sunny Jin

**Data & AI engineering**

I build data and AI systems that hold up in production: document extraction with
verification gates, retrieval over messy corpora, and SQL and BI that the people
using it can actually trust.

Three years across public-sector data migration, document AI for a commercial
client, and analytics for manufacturing and procurement operations.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-0F172A?style=flat-square&logo=langgraph&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

## Selected work

**50k+ records migrated, no post-go-live data loss** — public-sector platform
migration. Ran UAT with 12+ user groups and reviewed RBAC end to end; removed
1,300+ inappropriate access grants, and a later central audit by the operating
agency found none remaining.
[Write-up](https://sunnyjin2002.github.io/experience.html)

**Non-standard invoices turned into validated records** — client work, anonymised.
Multimodal LLM for OCR, deterministic matching for predictable fields, the LLM
reserved for ambiguous regions, every output gated behind a verification pass.
Accuracy was measured on a hand-labelled sample; the method and its limits are in
the write-up. [Write-up](https://sunnyjin2002.github.io)

**Quality-inspection platform, full stack** — client work, anonymised. Vue, Django,
PostgreSQL, Redis and MinIO on Linux, with async LLM inference and automatic
flagging of discrepancies for human review.
[Write-up](https://sunnyjin2002.github.io)

**Production scheduling: constraints before code** — scoped the constraint set and
objective weights against historical factory data before any optimiser was
written. Requirement and model design, not a shipped solver.
[Write-up](https://sunnyjin2002.github.io/portfolio.html)

Private client work. Write-ups describe approach and results; source code stays
with the client and implementation walkthroughs are available on request.

## What I work on

- **Document AI and structured extraction** — turning inconsistent scans and PDFs
  into records you can trust, with the verification step designed in rather than
  bolted on afterwards
- **RAG and LLM workflow engineering** — retrieval design, checking what the model
  returns, and what each query costs to serve
- **Analytics and BI** — SQL modelling, data validation, KPI reporting, and
  dashboard requirements that survive contact with the people using them

## Repositories

- **[EDAMA](https://github.com/sunnyjin2002/EDAMA)** — glossary-guided translation
  pipeline: controlled vocabulary, translation memory, the LLM only for ambiguous
  passes, human submission step. FastAPI, Next.js, Chroma, LangGraph. Retrieval
  chatbot in progress.
- **[tick-stock-panel](https://github.com/sunnyjin2002/tick-stock-panel)** —
  contributed a volume-profile (筹码峰) feature to an MIT-licensed quant dashboard:
  data model, phased backend and frontend work, historical recompute. This is a
  fork.
- **[sunnyjin2002.github.io](https://github.com/sunnyjin2002/sunnyjin2002.github.io)**
  — this site, hand-built static HTML.

## Connect

Portfolio and case studies — **[sunnyjin2002.github.io](https://sunnyjin2002.github.io)**  
LinkedIn — **[sunny-jin-19692b222](https://www.linkedin.com/in/sunny-jin-19692b222)**  
Email — **[sunnyjin2002@hotmail.com](mailto:sunnyjin2002@hotmail.com)**

Open to data analyst, AI/data engineering and business analyst roles in Hong Kong.
If the work above looks adjacent to what you're building, get in touch.
