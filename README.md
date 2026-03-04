# Retail Sales & Profitability Analysis

## Project Overview

This project analyzes transactional retail sales data to evaluate revenue performance, profit contribution, and margin trends across products, categories, and time periods.

The objective was to identify key profit drivers, understand seasonal performance patterns, and assess category-level margin efficiency.

---

## Dataset Description

The dataset contains transaction-level retail sales records with the following key fields:

- `sales_date`
- `store_id`
- `product_id`
- `units_sold`
- `gross_sales`
- `discount_amount`
- `net_sales`
- `cost_price`
- `gross_profit`
- `gross_profit_margin`
- `category`
- `region`

The analysis focuses on revenue and profitability metrics derived from these fields.

---

## Analysis Performed
## KPIs Analyzed

- **Total Net Sales**
- **Total Gross Profit**
- **Gross Profit Margin (%)**
- **Revenue Contribution (%)**
- **Profit Contribution (%)**
- **Monthly Revenue & Profit Trend**

---

## Analysis & Findings


### 1. Monthly Revenue & Profit Trend

<img width="1324" height="422" alt="Screenshot 2026-03-04 at 11 22 09 PM" src="https://github.com/user-attachments/assets/08b4f0c7-9a0c-4fa9-9b91-f152a4964dc0" />

- Revenue contribution increased significantly in October (22.48%) and November (21.81%) compared to the June–September average (~13%).
- Profit contribution also increased in October (23.11%) and November (22.38%).
- Gross profit margin improved from ~54% (June–September average) to ~57% in October and November.

**Insight:**  

Revenue growth in the later months was accompanied by margin expansion, indicating profitable seasonal growth rather than discount-driven sales.

---

### 2. Category-Level Revenue & Profit Contribution

<img width="1299" height="316" alt="Screenshot 2026-03-04 at 11 21 55 PM" src="https://github.com/user-attachments/assets/66e56886-a380-4541-a1a7-b4a37a5abdd8" />

- Accessories contributed approximately **25%+ of total profit**, making it the highest profit-driving category.
- Gift Packs also showed strong profit contribution during peak months.
- Some categories generated high revenue but relatively lower profit contribution, indicating lower margin efficiency.

**Insight:**  
Accessories and Gift Packs were the strongest performing categories in terms of both profit contribution and margin efficiency.

---

### 3. Revenue Share vs Profit Share Comparison

Revenue and profit contribution were compared to identify true performance drivers:

- Categories where **profit share exceeded revenue share** demonstrated higher-than-average margins.
- Categories where **revenue share exceeded profit share** indicated relatively lower margins.

**Insight:**  
High-margin categories were responsible for a disproportionate share of total profit, highlighting the importance of product mix in driving profitability.
---

## Key Insights

- Revenue and profit both increased in the later months, indicating seasonal demand impact.
- Profit margins improved alongside revenue growth, suggesting profitable expansion rather than discount-driven growth.
- Certain categories contributed disproportionately to total profit due to stronger margin efficiency.
- Comparing revenue share vs profit share provided better visibility into true performance drivers.

## Recommendations
Prioritize high-margin categories (e.g., Accessories, Gifts) through targeted promotions and better product placement to maximize profitability.
Optimize product mix by increasing the share of categories where profit contribution exceeds revenue contribution.
Investigate low-margin, high-revenue categories to identify pricing, discounting, or cost inefficiencies.
Analyze month-over-month margin trends to determine drivers behind recent profitability improvements.
Expand analysis to customer-level insights (repeat rate, average order value, category affinity) to support long-term revenue growth.

---

## KPIs Evaluated

- Net Sales
- Gross Profit
- Gross Profit Margin (%)
- Revenue Contribution (%)
- Profit Contribution (%)

---

## Tools Used

- Microsoft Excel
  - Pivot Tables
  - Calculated Fields
  - Contribution Analysis
  - Trend Analysis

---

## Conclusion

This project demonstrates structured retail revenue and profitability analysis using transactional data. The focus was on interpreting business performance through contribution metrics and margin trends rather than surface-level sales figures.
