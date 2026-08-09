# SQL Data Analytics Project

An end-to-end SQL Data Analytics project establishing a Star Schema Data Warehouse (`gold` layer) in Microsoft SQL Server to analyze business sales, product performance, and customer metrics.

---

## About The Project

This project transforms raw transactional sales, product catalog, and customer demographic data into a structured Data Warehouse (`DataWarehouseAnalytics`). It provides business insights using T-SQL across key analytical domains:

- **Data Warehouse Modeling:** Implements a Star Schema architecture featuring dimension tables (`gold.dim_customers`, `gold.dim_products`) and a central fact table (`gold.fact_sales`).
- **Exploratory Data Analysis:** Examines core business metrics, customer demographics, order lifespans, and product line distributions.
- **Advanced SQL Analytics:** 
  - **Ranking & Performance:** Ranks top-performing products and high-value customers using window functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`).
  - **Time-Series & Trend Analysis:** Tracks Month-over-Month (MoM) and Year-over-Year (YoY) revenue momentum.
  - **Cumulative & Benchmark Metrics:** Calculates running revenue totals and evaluates product variance against category averages.
  - **Data Segmentation & Part-to-Whole:** Classifies customers into RFM/spending tiers (VIP, Regular, New) and calculates category contributions to total revenue.
- **Executive Reporting Views:** Establishes reusable analytics views (`gold.report_customers` and `gold.report_products`) consolidating customer lifespan, purchase recency, order frequency, and product revenue performance.

---

<div align="center">
  <b>Developed by <a href="mailto:minitchitroda@gmail.com">Minit Chitroda</a></b>
</div>
