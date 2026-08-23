# 06 · Business Rules

| ID | Rule | Category |
|---|---|---|
| BR-01 | Orders with status "Returned" are excluded from Total Revenue, Avg. Transaction, and Units Sold calculations. | Data / Finance |
| BR-02 | Customer loyalty status is determined by annual spend: Basic (<$500), Silver ($500–$1,500), Gold ($1,500–$3,000), Platinum (>$3,000). | Loyalty |
| BR-03 | Revenue Margin = (Revenue − Cost of Goods Sold) / Revenue, calculated separately per category. | Finance |
| BR-04 | All financial figures shown on the dashboard are displayed in the reporting currency (EUR or USD by region), converted at real-time exchange rates. | Finance |
| BR-05 | PivotTable results must be reconciled against the source transaction table at month-end; a discrepancy greater than 0.5% triggers an alert. | Data Quality |
| BR-06 | Only the Regional Sales Director and higher-privilege users can access data across all regions; store-level users see only their own store. | Access Control |
| BR-07 | Category revenue percentages (donut chart) are calculated using only non-cancelled orders. | Data / Finance |
