# Customer Churn KPI Dashboard

Interactive dashboard built from `customer_churn_sample.csv` (single-file HTML, no dependencies).

**KPIs:** churn rate, retention rate, revenue lost, revenue at risk, average tenure.
**Filters:** contract type, tenure band, payment method.
**Charts:** churn rate by contract, tenure and payment method; revenue at risk by subscription. Colour-blind-safe palette, light/dark mode.

## Run
Open `index.html` in a browser, or enable GitHub Pages (Settings > Pages > main / root) for a public link.

## Definitions
- Churn rate = churned / total customers; Retention = 1 - churn rate
- Revenue lost = monthly charges of churned customers
- Revenue at risk = monthly charges of active customers on Month-to-Month contracts or with 3+ support tickets
- Tenure bands: 0-12, 13-24, 25+ months
