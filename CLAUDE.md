# Data Science Manager — Interview Prep

## Target JD: BAT (British American Tobacco)
- **Job Title**: Data Science Manager
- **Company**: BAT — Digital Business Solution team
- **Location**: Subang Jaya, Malaysia
- **Reports to**: APMEA North Head of D&A
- **Team size**: 1 internal + 2 contractors
- **Geographic Scope**: Global

### JD Key Themes
- End-to-end ML/analytics lifecycle: problem framing → data exploration → modeling → validation → deployment
- Models: segmentation, churn propensity, uplift modeling, forecasting, clustering
- Data from **Microsoft Fabric / Data Warehouse** using **T-SQL + Python**
- Cross-functional: works with Business Analysts, BI Developers, Data Engineers, Solution Managers
- MLOps: CI/CD, model monitoring, automated retraining (preferred)
- Analytics governance, documentation, explainability, responsible AI
- Azure cloud environment

### JD Requirements
- 7+ years data science/analytics, 3+ years management
- SQL/Python hands-on, 2+ ML models deployed to production
- Azure or similar cloud, MLOps components
- FMCG/retail/consumer insights domain is a plus

### Fit Notes
- Strong match: team leadership, data engineering coordination, pipeline/lakehouse, governance, cross-functional collaboration
- Angle to emphasize: DS/modeling experience (dimensional modeling, analytics enablement), model lifecycle, data quality
- Scale framing: smaller team (1+2) — position as intentional focus on technical depth over headcount

---

## Role Context
- **Position**: Data Science Manager
- **Company**: BAT (British American Tobacco) — Digital Business Solution
- **Product**: Advanced analytics & ML solutions — segmentation, churn, uplift modeling, forecasting; data from Microsoft Fabric/DWH
- **Team**: 1 internal + 2 contractors; cross-functional with BAs, BI Devs, Data Engineers, Solution Managers
- **Round**: Technical interview
- **Interviewer**: Expects technical depth in DS/ML modeling + lifecycle management + leadership credibility; reports to APMEA North Head of D&A
- **Format**: 1 hour, screen-share slides as conversation anchors (not a presentation)

## Interview Strategy
**Focus on past real experience.** Every slide backs a real story. No generic best practices.
Slides are shown on screen share — they guide conversation, not replace it.
The interviewer will interrupt and dig in. That is expected and good.

## Candidate Background
- **Team size**: Led 13+ engineers across multiple squads (peak)
- **Domains**: Data engineering · Data analytics · Data science/modeling · IAM & RBAC · Agentic AI · Payment systems
- **Streaming**: Kafka · Flink · KSQL · realtime pipelines · exactly-once semantics
- **Storage**: Lakehouse (bronze/silver/gold) · Data warehouse · ETL/ELT
- **Cloud**: AWS (ECS/EKS)
- **CI/CD**: GitLab CI
- **Monitoring**: Datadog, New Relic
- **Strongest technical areas**: Realtime streaming (exactly-once) · Data modeling (dimensional/star schema) · Lakehouse architecture · Multi-tenant data isolation · Event-driven architecture

## Slide Deck

### Single file: `slides/slides-app.html`
10 slides across 6 chapters. One continuous deck.

| Chapter | Slide | Content |
|---|---|---|
| 1. Who I Am | 1 | Title — name, role, tagline anchoring data engineering + data science blend |
| 1. Who I Am | 2 | Career Snapshot — timeline, team sizes, platform scale, key metrics |
| 2. Systems I've Built | 3 | Data Platform Architecture — ingestion → Kafka → Flink/KSQL → Lakehouse → serving |
| 2. Systems I've Built | 4 | Technical Decisions — streaming vs batch, warehouse selection, orchestration, schema registry |
| 2. Systems I've Built | 5 | Outcomes by Numbers — pipeline SLA, data freshness, cost reduction, adoption |
| 3. Team I've Led | 6 | Squad Structure + Culture — data engineers + data scientists + analytics engineers, avoiding silos |
| 4. Hard Problems | 7 | Hard Problem: Data Engineering — Realtime streaming exactly-once at scale (Kafka + Flink/KSQL) |
| 4. Hard Problems | 8 | Hard Problem: Data Analytics/Modeling — Data modeling decisions (dimensional modeling, star schema, SCD handling) |
| 5. Engineering Foundation | 9 | Data Quality + Observability — data SLAs, lineage, quality checks in pipeline, alerting |
| 6. Closing | 10 | Why This Role — past experience mapped to what this role needs |

## Framing Notes
- **Primary lens**: This is a DS-first role — lead with modeling, ML lifecycle, and analytics insight delivery. DE background is a differentiator, not the headline.
- **Hard problem DS**: Data analytics/modeling — dimensional modeling decisions, star schema vs data vault, slowly changing dimensions (SCDs), semantic layer design.
- **Hard problem DE**: Realtime streaming — exactly-once semantics with Kafka + Flink, late/out-of-order event handling, what broke first. Reframe as: "infra I built to feed clean data into models."
- **MLOps angle**: Tie CI/CD (GitLab CI) and monitoring (Datadog/New Relic) experience to model deployment pipelines and production model monitoring — BAT explicitly wants MLOps.
- **Azure gap**: Candidate background is AWS — acknowledge, bridge to transferable cloud fundamentals and prior work with similar managed services.
- **Team hiring**: Frame slides as "what I look for" and "how I structure the team" rather than claiming direct hire authority.
- **Scale framing**: BAT team is 1+2 — don't lead with "13+ engineers." Position as: led at scale, now focused on technical depth and direct delivery.

## Remaining Placeholders
- Slide 10 (closing) still uses general language — needs to be updated for BAT specifically (APMEA D&A, analytics product delivery, FMCG/commercial analytics context).

## Build Notes
- Template system: Inter + DM Serif Display fonts, CSS custom properties, card/grid/timeline components
- PDF export: measures natural slide height per page (no whitespace)
- Component classes: `.card .c-*`, `.g2`, `.g3`, `.tl`, `.metrics`, `.infobar`, `.comms`
- New in interview-prep: `.ph` (placeholder highlight), `.arch` (architecture diagram), `.split-story`
