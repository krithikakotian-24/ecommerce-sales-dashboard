# E-Commerce Sales Dashboard

An end-to-end sales analytics project — from raw data to an interactive Power BI dashboard.

##  Tools Used
- **Python (Pandas)** — data cleaning, validation, and preprocessing
- **SQL (SQLite)** — exploratory analysis and revenue queries
- **Power BI (DAX)** — interactive dashboard with dynamic measures and slicers

##  Project Workflow
1. **Data Cleaning** — Handled missing values, verified duplicate records, and corrected TotalPrice calculation mismatches across 1,200 orders
2. **SQL Analysis** — Queried revenue by product, coupon usage impact, and referral source performance
3. **Dashboard Design** — Built a 2-page Power BI report with KPI cards, trend analysis, and customer segmentation

##  Dashboard Pages

**Page 1 — Sales Overview**
- KPI cards: Total Revenue, Total Orders, Avg Order Value
- Revenue trend by month
- Revenue by product
- Orders by referral source
- Order status breakdown by product
- Interactive Date range & Order Status slicers

**Page 2 — Customer & Payment Insights**
- Cancellation rate
- Coupon usage impact on order value
- Top 10 customers by revenue
- Revenue by payment method

##  Key Insights
- Chair and Printer were the top revenue-generating products (~$195K each)
- Referral sources were evenly distributed across Instagram, Email, Google, Facebook, and Referral (~18–22% each)
- 20.83% of orders were cancelled — a notable area for operational improvement
- Orders using a coupon had a slightly higher average order value ($1,057.64) than those without ($1,043.37)

##  Files
- `e commerce sales dashboard.pbix` — Power BI report file
- Data cleaning and SQL analysis notebooks (linked in related repo/portfolio)
