# 03 · Data & Dashboard

## Data Source & Methodology

This section presents two dashboards built on a synthetic retail sales dataset created for the "Atlas Office Supplies / Carrefour Retail" simulation: (1) an overall sales performance panel, and (2) a deep-dive customer analysis panel for the Gold loyalty segment. The dataset covers **5,000 transactions**, **8 product categories**, and **4 loyalty statuses** (Basic, Silver, Gold, Platinum).

> See [`/dashboard/index.html`](../dashboard/index.html) for an interactive recreation of the charts below. Note: individual segment revenue values are illustrative approximations for the demo chart, since the original dashboard shows relative bar heights rather than exact figures.

## Overall Sales Performance Panel

**Headline metrics:**

| Metric | Value |
|---|---|
| Total Revenue | $522,367 |
| Transactions | 5,000 |
| Units Sold | 19,951 |
| Avg. Transaction Value | $104.47 |

**Key observations:**

- **Revenue by loyalty status:** Basic generates the highest revenue, with Platinum close behind. Silver is mid-range, and Gold has the lowest overall revenue — suggesting either a smaller customer base or lower purchase frequency in that segment (see the Gold deep-dive below).
- **Annual revenue trend:** Monthly revenue fluctuates between €33,000 and €45,000, peaking in April and July (likely seasonal campaigns or pre-holiday shopping) and dipping to its lowest point in September.
- **Category revenue split:** Dairy leads with 19%, followed by Bakery (17%) and Grocery (15%). Beverages has the smallest share at 8%.
- The $104.47 average transaction value is consistent with a typical supermarket-format basket size.

## Gold Loyalty Segment — Deep-Dive Customer Analysis

| Metric | Value |
|---|---|
| Gold Segment Revenue | $105K |
| Revenue Margin | 23% |
| Units Sold | 4,518 |
| Bakery Units | 1,059 (23% of Gold sales) |

**Key observations:**

- Gold's 23% margin is the key comparison metric — even though total revenue is lower, this margin suggests Gold customers may be the most profitable segment per unit of revenue.
- Bakery is the top category within Gold too (1,059 units, 23% of segment sales), consistent with the overall dashboard trend.
- Fresh Produce (14%) and Dairy (12%) rank second and third within Gold; Personal Care is lowest at just 6%.
- This finding points to a need for additional cohort analysis (e.g., customer count, visit frequency) to explain why Gold has the lowest overall revenue share — flagged as a separate requirement in [Document 05](05-requirements.md).

## Data Quality Notes

Early in the analysis it became clear that returned orders needed to be fully excluded from revenue calculations, otherwise Total Revenue and Avg. Transaction figures could be inflated. It was also noted that PivotTable-based reports needed to be reconciled against the source data, and charts needed correct axes/scaling. These notes came out of feedback on the first draft of the Regional Sales Performance Review and were formalized as a business rule in [Document 06](06-business-rules.md).
