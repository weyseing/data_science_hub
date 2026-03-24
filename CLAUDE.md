# Data Engineering Manager — Interview Prep

## Role Context
- **Position**: Data Engineering Manager (mix of Data Engineering + Data Science/Analytics)
- **Company**: General — not company-specific
- **Product**: Data platform — realtime streaming pipelines, lakehouse/data warehouse, analytics, ML/data science enablement
- **Team**: Manager leading a mixed squad of data engineers + data scientists + analytics engineers
- **Round**: Technical interview
- **Interviewer**: Expects technical depth across both data engineering and analytics/data science + leadership credibility
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
- **Mixed discipline**: Frame as a leader who bridges data engineering (pipelines, infra) and data science/analytics (modeling, insight delivery) — not purely one or the other.
- **Hard problem DS**: Data analytics/modeling — dimensional modeling decisions, star schema vs data vault, slowly changing dimensions (SCDs), semantic layer design.
- **Hard problem DE**: Realtime streaming — exactly-once semantics with Kafka + Flink, late/out-of-order event handling, what broke first.
- **Team hiring**: Frame slides as "what I look for" and "how I structure the team" rather than claiming direct hire authority.
- **Scale awareness**: Calibrate examples to the actual team size context — avoid enterprise-only patterns.

## Remaining Placeholders
No open placeholders. Slide 10 (closing) uses general language — reusable across roles.

## Build Notes
- Template system: Inter + DM Serif Display fonts, CSS custom properties, card/grid/timeline components
- PDF export: measures natural slide height per page (no whitespace)
- Component classes: `.card .c-*`, `.g2`, `.g3`, `.tl`, `.metrics`, `.infobar`, `.comms`
- New in interview-prep: `.ph` (placeholder highlight), `.arch` (architecture diagram), `.split-story`
