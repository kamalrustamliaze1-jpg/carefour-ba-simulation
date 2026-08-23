# 05 · Requirements

## Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The system shall display revenue by store, region, and loyalty status in near real-time (≤24 hour lag). | High |
| FR-02 | The system shall automatically detect returned orders and exclude them from Total Revenue calculations. | High |
| FR-03 | The user shall be able to view category revenue split in a donut chart. | Medium |
| FR-04 | The system shall provide separate deep-dive panels for each loyalty status (Basic, Silver, Gold, Platinum). | High |
| FR-05 | The user shall be able to track the annual/monthly sales trend in a line chart. | Medium |
| FR-06 | The system shall provide automatic reconciliation of PivotTable data against the source dataset. | High |
| FR-07 | The user shall be able to export the dashboard as PDF or PowerPoint. | Low |
| FR-08 | The system shall merge e-commerce (online) and physical store sales into a single data model (omnichannel). | High |
| FR-09 | Role-based access control: a Store Manager sees only their own store's data; a Regional Director sees the full region. | High |

## Non-Functional Requirements

| Category | Requirement |
|---|---|
| Performance | Dashboard shall load in under 3 seconds (for 10,000+ transactions). |
| Scalability | System shall support 15,000+ stores and millions of daily transactions. |
| Security | Data shall be stored and transmitted in compliance with GDPR (Europe). |
| Reliability | System uptime shall be ≥ 99.5%. |
| Usability | Non-technical store managers shall be able to use core functions without additional training. |
| Auditability | All data changes (especially returns corrections) shall be logged with an audit trail. |
