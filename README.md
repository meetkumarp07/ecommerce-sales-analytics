# 🛒 Olist E-Commerce Analytics Dashboard

## Overview
End-to-end exploratory data analysis and interactive dashboard project built on the Olist Brazilian E-Commerce public dataset — 100,000+ real orders across 2016–2018.

## Key Findings
- 💰 **Total Revenue:** BRL 16M across 2 years
- 📦 **Total Orders:** 99,441 orders processed
- 🚚 **On-Time Delivery:** 91.9% — consistently above 90% target
- ⭐ **Average Review Score:** 4.1/5 — strong customer satisfaction
- 🗺️ **São Paulo dominates:** 40% of all orders from SP state
- 💳 **Credit card:** 78.3% of all payments
- 📈 **Peak revenue:** November 2017 — Black Friday effect

## Dashboards
| Dashboard | Description |
|---|---|
| KPI Dashboard | Executive summary — 8 KPI cards + trends |
| Master Dashboard | 9 charts — full analytics overview |
| Revenue Dashboard | Monthly revenue and order volume trends |
| Category Dashboard | Top 10 product categories by revenue |
| Customer Segmentation | RFM analysis — High/Mid/Regular/Low value |
| Delivery Dashboard | On-time rate, delivery days, distribution |

## Tech Stack
- **Python** — pandas, pandasql, plotly, matplotlib, seaborn
- **SQL** — pandasql for data extraction and aggregation
- **Plotly** — interactive HTML dashboards
- **Dataset** — Olist Brazilian E-Commerce (Kaggle)

## Project Structure
- `notebooks/01_sql_analysis.ipynb` — Full analysis notebook
- `dashboard/kpi_dashboard.html` — Executive KPI summary
- `dashboard/master_dashboard.html` — Master analytics view
- `dashboard/revenue_dashboard.html` — Revenue trends
- `dashboard/category_dashboard.html` — Category performance
- `dashboard/customer_segmentation.html` — RFM segmentation
- `dashboard/delivery_dashboard.html` — Delivery analytics

## Business Insights
1. **São Paulo opportunity** — SP generates 40% of revenue with highest order volume. Marketing budget should prioritize SP and RJ markets.
2. **Black Friday impact** — November 2017 showed peak revenue spike. Recommend inventory planning 6 weeks ahead of November each year.
3. **Delivery improvement** — 8.1% late delivery rate correlates with lower review scores. Logistics audit recommended for March 2018 drop to 78.6% on-time rate.
4. **Credit card dominance** — 78.3% of payments via credit card. Recommend credit card partnerships and installment payment promotions.
5. **Customer retention gap** — 96% of customers are one-time buyers. Loyalty program could significantly increase lifetime value.

## Author
**Meetkumar Patel**
- M.Sc. Big Data Analytics — Trent University
- LinkedIn: linkedin.com/in/meetkumarpatel
- Email: meetkumarp11@gmail.com
