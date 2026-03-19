# 🛒 Olist E-Commerce Analysis

## Overview
End-to-end data analysis project on Olist Brazilian 
E-Commerce dataset using BigQuery, SQL, and Power BI.

## Key Insights
- 📦 96,000+ orders analyzed across 3 years (2016-2018)
- 💰 Total Revenue: 13.22M BRL
- 🚚 Late Delivery Rate: 8.11% — structural issue across all years
- 📈 Consistent YoY growth with peak in November 2017 (987K)
- 👥 97% of customers never returned after first purchase

## Business Recommendations
1. Launch Loyalty Program — converting 5% of one-time buyers adds significant revenue
2. Focus 60% of marketing budget on Top 3 Categories (25.76% of revenue)
3. Open warehouses in high late-rate regions to reduce delays below 5%
4. Double inventory and staff in October-November (peak season)
5. Investigate sales drop from July 2018 — possible competitive threat
6. Bundle offers for cama_mesa_banho to increase Average Order Value
7. Invest in post-purchase experience to improve retention
8. Premium packaging for relogios_presentes (highest avg price: 201 BRL)

## Tools & Technologies
| Tool | Usage |
|------|-------|
| BigQuery | Data storage + SQL analysis |
| SQL | 5 analytical views + Window Functions + CTEs |
| Power BI | Dashboard + DAX measures |
| DAX | KPIs + YoY calculations |

## Dashboard
🔗 [Live Dashboard](https://app.powerbi.com/links/F2C5RKMC6Y?ctid=5cb6ce2a-2f85-4834-8578-a9a8caac5d6f&pbi_source=linkShare)

## SQL Views
- `vw_monthly_revenue` — Monthly sales trend
- `vw_top_categories` — Top performing categories
- `vw_delivery_performance` — Delivery analysis by state
- `vw_rfm_segments` — Customer segmentation
- `vw_yoy_growth` — Year-over-year comparison

## Dataset
Source: [Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
