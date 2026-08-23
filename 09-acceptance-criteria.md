# 09 · Acceptance Criteria (Given / When / Then)

| User Story | Given | When | Then |
|---|---|---|---|
| US-01 | The user is logged in as Regional Sales Director | The user selects the "All Regions" view | The system displays revenue, transaction, and unit metrics for each region within 3 seconds |
| US-02 | The user has selected the Gold segment | The user clicks "Deep-Dive Analysis" | The system opens a separate panel showing Gold's margin, category split, and unit sales |
| US-03 | At least 1 returned order exists in the reporting period | The user views the Total Revenue metric | The returned order's value is excluded from Total Revenue, and this is reflected in the audit log |
| US-04 | The user is logged in as a Store Manager | The user opens the dashboard | The system shows only that user's assigned store data; access to other stores is blocked |
| US-05 | Monthly reconciliation discrepancy exceeds 0.5% | The system completes the nightly ETL process | An automatic email/system alert is sent to the Business Analyst, and the source of the discrepancy is logged |
| US-06 | The user has selected any date range | The user views the monthly trend chart | The system displays the monthly revenue trend for the selected period as a correctly-scaled line chart |
