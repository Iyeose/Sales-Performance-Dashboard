# Sales Performance Dashboard

A data analysis and business intelligence project using **Excel**, **SQL**, and **Tableau** to explore and visualize retail sales data from the Superstore dataset.

---

## Project Overview

This project analyzes Superstore sales data to uncover insights about regional performance, product trends, and profitability. It demonstrates practical skills in:

-  Data cleaning and preparation (Excel)
-  Querying and aggregating sales metrics (SQL)
-  Creating dynamic dashboards and visual stories (Tableau)

---

## Dataset

- **Source**: [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **File Used**: `Smaple-Superstore.csv`
- Contains records of orders, products, customers, and sales from a fictional US-based retail business.

---

## Tools & Technologies

| Tool        | Purpose                                 |
|-------------|------------------------------------------|
| **Excel**   | Data cleaning, calculated fields         |
| **SQLite**  | SQL queries and trend analysis           |
| **Tableau** | Data visualization and dashboards        |
| GitHub      | Version control and documentation        |
---

## Project Steps

### 1. Data Cleaning (Excel)
- Parsed and reformatted `Order Date` and `Ship Date`
- Added derived fields: Year, Month, Profit Margin
- Removed duplicates and standardized values

### 2. Data Analysis (SQL)
Key queries:
- Total sales and profit by region
- Monthly sales and profit trends
- Top 10 best-selling products
- Profit margin by product category

See [`SQL_queries.sql`](https://github.com/Iyeose/Sales-Performance-Dashboard/blob/main/sample_superstore_SQL.txt) for full list of SQL commands.

### 3. Dashboard Overview

### ✅ Metrics Tracked:
- **Total Sales** and **Profit**
- **Top States and Sub-Categories by Sales**
- **Regional Sales Distribution**
- **Customer Growth Over Time**
- **Segment Performance**
- **Profit Margins by Product Category**
- **Monthly Trends (Profit & Sales)**
---

##  Tableau Dashboard Screenshot

![Superstore Dashboard](images/Superstore%20Sales%20Performance.jpg)

> _You can download or view the full resolution image [here](https://public.tableau.com/views/SuperstoreSalesPerformance_17541649793780/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📈 Key Insights

- **California** leads all states in total sales, with over \$450,000 in revenue.
- The **West** and **East** regions are top contributors to total revenue.
- **Phones** and **Chairs** are the highest-selling sub-categories.
- **Technology** and **Office Supplies** yield the highest profit margins.
- Sales and profit have shown a steady increase from 2014 to 2017.
- **Consumer segment** drives the largest share of sales.

---
