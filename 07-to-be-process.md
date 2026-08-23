# 07 · To-Be Process & Solution

## Solution Overview

The proposed To-Be model merges store POS, e-commerce platform, and loyalty program data into a central cloud-based data warehouse — an architecture consistent with Carrefour's already-announced Unlimitail (data/retail media) and ai.carrefour AI platform initiatives. Automated ETL (Extract-Transform-Load) pipelines clean and consolidate returns, discounts, and channel (online/offline) data on a daily basis.

## To-Be Process Flow (BPMN — text description)

| # | Step | Owner / System | Automation Level |
|---|---|---|---|
| 1 | Real-time streaming of POS and e-commerce transactions | POS + E-commerce API | Fully automated |
| 2 | Data validation and returns/cancellation filtering (applies BR-01) | ETL engine | Fully automated |
| 3 | Central data warehouse consolidation (across all regions/formats) | Cloud Data Warehouse | Fully automated |
| 4 | Automated reconciliation check and alerting | BI engine + Alert system | Fully automated |
| 5 | Role-based live dashboard delivery | BI Platform (Power BI / Tableau) | Fully automated |
| 6 | Exception (anomaly) review | Business Analyst | Semi-automated |
| 7 | Decision-making and action planning | Regional Sales Director | Human decision |

## As-Is vs To-Be

| Aspect | As-Is (Current) | To-Be (Proposed) |
|---|---|---|
| Data refresh | Quarterly / manual | Near real-time (24 hours) |
| Returns handling | Separate log, manually excluded | Automatic filter (BR-01) |
| Channel integration | Physical and online separate | Unified omnichannel model |
| Error risk | High (manual consolidation) | Low (automated ETL + validation) |
| Scalability | Limited | Fit for 15,000+ stores |
| Decision speed | 2–3 weeks | 1–2 days |

## Technology Components

- **Data layer:** Cloud-based data warehouse (e.g. Snowflake/BigQuery-type), daily ETL pipelines.
- **Analytics layer:** Power BI / Tableau-type BI tools, PivotTable/DAX-based calculation logic.
- **AI layer:** Machine learning models for anomaly detection (returns, unusual sales fluctuations), aligned with Carrefour's existing Hopla and Captana initiatives.
- **Access control:** Role-based access control (RBAC), SSO integration.
