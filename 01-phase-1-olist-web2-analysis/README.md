# 📊 Phase 1: Diagnosing the Pain

### *Uncovering logistics bottlenecks and trust erosion in Brazil's largest e-commerce marketplace*

[← Back to Main Project](../README.md)

---

## 🎯 Objective

Analyze the **Olist Brazilian E-commerce** dataset (100K+ orders) using SQL and Excel to expose two critical weaknesses of centralized e-commerce:

1. **🚚 Logistics Bottleneck** — Calculate delivery delays (estimated vs actual), identify worst-performing states and routes
2. **⭐ Review Fraud / Customer Discontent** — Prove that late deliveries → 1-star reviews → customer churn

## 📊 Dataset

Source: [Olist Brazilian E-commerce (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

| Table | Description |
|-------|-------------|
| `olist_orders_dataset` | Order timestamps & status |
| `olist_order_items_dataset` | Items, sellers, prices |
| `olist_order_reviews_dataset` | Customer reviews (1-5 stars) |
| `olist_order_payments_dataset` | Payment methods & values |
| `olist_customers_dataset` | Customer locations |
| `olist_sellers_dataset` | Seller locations |
| `olist_products_dataset` | Product details |
| `olist_geolocation_dataset` | Lat/long coordinates |
| `product_category_name_translation` | Category translations |

## 🔧 Tools

- ✅ **SQL** (Google BigQuery) — Complex analytical queries
- ✅ **Excel** — Pivot tables, charts, initial exploration
- 🔜 **Power BI** — Interactive dashboards *(coming soon)*
- 🔜 **Tableau** — Data visualization *(coming soon)*

## 📂 Structure *(will be expanded)*

```
phase-1-olist-web2-analysis/
├── README.md        ← You are here
├── data/            ← Olist CSV datasets
├── sql/             ← SQL query files
├── excel/           ← Excel analysis files
├── visualizations/  ← Power BI & Tableau (coming soon)
└── findings/        ← Key findings & conclusions
```

## 🔑 Key Questions

- Which Brazilian states have the worst delivery performance?
- What is the average delay between estimated and actual delivery?
- Is there a correlation between late delivery and 1-star reviews?
- What is the estimated financial impact of logistics failures?
- What is the churn rate for late deliveries vs on-time?

## 📈 Findings

> 🔜 *Analysis in progress — findings will be updated here.*

## ➡️ Next

> *The findings from this analysis reveal a critical trust deficit in centralized e-commerce. Phase 2 proposes a blockchain-based solution to address these systemic failures.*

**[→ Continue to Phase 2: Web3 Escrow Solution](../02-phase-2-web3-escrow-solution/)**
