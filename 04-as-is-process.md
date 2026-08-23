# 04 · As-Is Process & BPMN

## Process Overview

Currently, Carrefour's regional sales reporting process runs mainly on separate Excel exports from store POS systems, weekly consolidation in the central ERP, and quarterly manually-built PowerPoint presentations. The e-commerce channel's rapid growth (+21% GMV in 2025) isn't integrated with physical store data at the same pace, so there is no single source of truth.

## As-Is Process Flow (BPMN — text description)

| # | Step | Owner | Input / Output |
|---|---|---|---|
| 1 | Daily sales data export from store POS | Store Managers | In: POS transactions → Out: CSV/Excel file |
| 2 | File sent to regional office by email | Store Managers | In: CSV file → Out: Email |
| 3 | Manual consolidation of files (Excel) | Regional Analyst | In: Multiple files → Out: Consolidated table |
| 4 | Returns checked in a separate report | Finance Controller | In: Returns log → Out: Correction entries |
| 5 | Manual PivotTable and chart creation | Regional Analyst | In: Consolidated data → Out: Dashboard/report |
| 6 | Quarterly presentation delivered to leadership | Regional Sales Director | In: Report → Out: Decision / feedback |

## Simplified Flow Diagram

`[Store POS] → [Excel export] → [Email transfer] → [Manual consolidation] → [Returns check (separate)] → [PivotTable/Chart prep] → [Quarterly PPT presentation] → [Leadership decision]`

## Identified Pain Points

- **Delay:** 2–3 weeks pass from data collection to decision, because the process is manual and quarterly.
- **Error risk:** Manual consolidation is exposed to human error (formula mistakes, outdated file versions).
- **Returns separation:** Returned orders are kept in a separate log rather than in the main report — inflating reported revenue.
- **Omnichannel disconnect:** Online (e-commerce) sales data doesn't merge with physical store data in the same system.
- **Doesn't scale:** A manual process isn't sustainable across 15,719 stores.
