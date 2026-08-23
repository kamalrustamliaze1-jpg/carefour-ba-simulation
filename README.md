# Carrefour Business Analyst Simulation
### Omnichannel & AI-Driven Retail Transformation — End-to-End BA Portfolio Project

**Author:** Kamal Rustamli · Baku Higher Oil School · August 2026

[[Report](Carrefour_BA_Simulation_Final_Report.pdf)]
[[Excel](Carrefour_Retail_Customer_Loyalty_Dashboard.xlsx)]
[[Dashboards](carrefour_dashboards.html)]
---

## About This Project

This is a full-cycle Business Analyst simulation built around **Carrefour**, Europe's largest and the world's second-largest retailer (15,719 stores, ~300,000 employees, €82.1B net sales in FY2025). The project walks through the complete BA lifecycle — from stakeholder discovery to KPI evaluation — applied to a realistic problem: Carrefour's traditional store operations and its fast-growing e-commerce arm (+21% GMV in 2025) are not integrated on a single, trustworthy data source.

The company context and financial figures are based on Carrefour's public FY2025 results. The dataset, internal processes, requirements, and business rules are original simulation material built to practice real BA deliverables end to end.

**Why this project:** Most BA portfolios show a single artifact (a dashboard, or a requirements doc). This one shows the *whole chain* — how a stakeholder need turns into a requirement, a business rule, a process redesign, and a measurable KPI — which is the actual job of a Business Analyst.

---

## What's Inside

| # | Document | What it demonstrates |
|---|----------|----------------------|
| 01 | [Project Brief](01-project-brief.md) | Business context, problem statement, scope (in/out) |
| 02 | [Stakeholder Analysis](02-stakeholder-analysis.md) | Stakeholder register, power/interest grid, RACI matrix |
| 03 | [Data & Dashboard](03-data-dashboard.md) | Synthetic retail dataset analysis, dashboard design, findings |
| 04 | [As-Is Process & BPMN](04-as-is-process.md) | Current-state process mapping, pain-point analysis |
| 05 | [Requirements](05-requirements.md) | Functional & non-functional requirements (FR/NFR) |
| 06 | [Business Rules](06-business-rules.md) | Formal business rule register (BR-01 to BR-07) |
| 07 | [To-Be Process & Solution](07-to-be-process.md) | Target-state architecture, As-Is vs To-Be comparison |
| 08 | [Use Cases & User Stories](08-use-cases-user-stories.md) | Use case catalog, user stories by persona |
| 09 | [Acceptance Criteria](09-acceptance-criteria.md) | Given/When/Then criteria per user story |
| 10 | [KPI & Evaluation](10-kpi-evaluation.md) | Project-level and business-level KPI framework |
| 11 | [Final BA Report](11-final-report.md) | Executive summary, findings, recommendations |

An interactive recreation of the dashboard's key charts (built with HTML/Chart.js) is in [`/dashboard`](dashboard/index.html) — open it directly in a browser or view it live via GitHub Pages (see setup below).

---

## Key Findings (Summary)

- **Loyalty revenue is uneven:** Basic and Platinum segments generate the most revenue; Gold is lowest overall — but carries the highest margin (23%), flagging it as a retention priority rather than a lost cause.
- **Category concentration:** Dairy (19%) and Bakery (17%) lead category revenue company-wide and within the Gold segment — a clear cross-sell opportunity.
- **Process risk:** The current (As-Is) sales reporting process is manual, quarterly, and takes 2–3 weeks from data to decision — unsustainable at Carrefour's scale (15,700+ stores).
- **Data quality gap:** Returned orders were not being excluded from revenue calculations, inflating reported figures — formalized as Business Rule BR-01 after review.

Full detail and the recommendation set are in the [Final BA Report](docs/11-final-report.md).

---

## Tools & Techniques Used

- **Excel** — PivotTables, PivotCharts, data cleaning, reconciliation checks
- **Business Analysis** — BPMN-style process mapping, RACI, MoSCoW-style prioritization, Given/When/Then acceptance criteria
- **Documentation** — structured BA deliverables (brief, requirements, business rules, KPI framework)
- **HTML/CSS/JavaScript (Chart.js)** — interactive dashboard recreation for this portfolio

---

## Repository Structure

```
carrefour-ba-portfolio/
├── README.md                     ← you are here
├── docs/                         ← all 11 BA deliverables, one file per document
│   ├── 01-project-brief.md
│   ├── 02-stakeholder-analysis.md
│   ├── ...
│   └── 11-final-report.md
├── dashboard/
│   └── index.html                ← interactive dashboard (Chart.js)
├── assets/
│   └── screenshots/               ← add your Excel dashboard screenshots here
└── Carrefour_BA_Simulation_Final_Report.pdf   ← original full report (all 11 docs, one file)
```

---

## How to View

- **Read online:** browse the `docs/` folder directly on GitHub — each `.md` file renders automatically.
- **Full PDF:** the original combined report is included at the repo root.
- **Live dashboard:** enable GitHub Pages (Settings → Pages → Source: `main` branch, `/dashboard` or root) and share the generated link on your CV/LinkedIn.

---

## Disclaimer

This is a simulation created for skill development. Carrefour's company profile and FY2025 financial figures are sourced from Carrefour's public results; the internal processes, dataset, requirements, and business rules are original coursework material and are not official Carrefour documents.

---

## Contact

**Kamal Rustamli**
Business Administration Student, Baku Higher Oil School
[LinkedIn - Kamal Rustamli](#) · [Email - kamal.rustamliaze1@gmail.com](#)
