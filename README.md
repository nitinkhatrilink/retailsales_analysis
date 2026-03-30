# retailsales_analysis
# Retail Sales Analysis (SQL)

## Overview

This project analyzes a retail sales dataset using SQL to answer common business questions related to sales performance, customer behavior, and product categories.

The goal is to practice and demonstrate core data analysis skills using PostgreSQL.

---

## Dataset

The dataset contains transactional sales data with the following fields:

* `transaction_id`
* `sale_date`
* `sale_time`
* `customer_id`
* `gender`
* `age`
* `category`
* `quantity`
* `price_per_unit`
* `cogs`
* `total_sale`

---

## Business Questions Solved

1. Retrieve all sales made on a specific date
2. Find transactions for Clothing category with quantity > 10 in Nov 2022
3. Calculate total sales for each category
4. Find average age of customers in Beauty category
5. Identify transactions with total sales greater than 1000
6. Count transactions by gender in each category
7. Analyze average monthly sales and identify best-selling months per year
8. Find top 5 customers based on total sales
9. Count unique customers per category
10. Segment sales into shifts (Morning, Afternoon, Evening)

---

## Key Concepts Used

* Filtering (`WHERE`)
* Aggregations (`SUM`, `AVG`, `COUNT`)
* Grouping (`GROUP BY`)
* Sorting (`ORDER BY`)
* Date handling (range filtering, month/year analysis)
* Window functions (for ranking and comparisons)
* Conditional logic (`CASE WHEN`)

---

## Sample Insights

* Certain categories contribute more to total revenue
* Sales vary significantly across months
* A small group of customers drives a large portion of sales
* Customer behavior differs across product categories

---

## Tools Used

* PostgreSQL
* SQL

---

## How to Run

1. Import the dataset into PostgreSQL
2. Create the required table using `schema.sql`
3. Run queries from `analysis.sql`

---

## Purpose

This project is part of my learning journey in data analytics, focusing on writing efficient SQL queries and deriving business insights from raw data.

---
