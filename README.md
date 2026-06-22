# DataX-Labs-Task-4
# SQL Data Analysis using MySQL

## Objective
Use SQL queries to extract and analyze data from an e-commerce database using MySQL Workbench.

## Dataset Used
Brazilian E-Commerce Public Dataset (Olist)

## Tools Used
- MySQL Workbench
- MySQL Server
- GitHub
- Olist E-commerce Dataset (CSV files)

## Database Name
ecommerce_db

## Tables Used
- olist_customers_dataset
- olist_orders_dataset
- olist_order_items_dataset
- olist_products_dataset

## Tasks Performed

### 1. SELECT Statement
Retrieved records from tables using SELECT.

### 2. WHERE Clause
Filtered data based on conditions.

### 3. ORDER BY Clause
Sorted records in ascending and descending order.

### 4. GROUP BY Clause
Grouped data and calculated counts.

### 5. JOINS
- INNER JOIN
- LEFT JOIN

Combined data from multiple tables.

### 6. Aggregate Functions
- SUM()
- AVG()
- COUNT()

Performed calculations on data.

### 7. Subqueries
Used nested queries for advanced filtering.

### 8. Views
Created views for simplified analysis.

### 9. Indexes
Created indexes to optimize query performance.

## Files Included
- day1_queries.sql
- olist_customers_dataset.csv
- olist_orders_dataset.csv
- olist_order_items_dataset.csv
- olist_products_dataset.csv
- Screenshots of query outputs

## Sample Queries

```sql
SELECT *
FROM olist_customers_dataset
LIMIT 10;

SELECT *
FROM olist_order_items_dataset
WHERE price > 100;

SELECT *
FROM olist_order_items_dataset
ORDER BY price DESC;

SELECT customer_id, COUNT(*) AS total_orders
FROM olist_orders_dataset
GROUP BY customer_id;
```

## Outcome
Learned to manipulate and analyze structured data using SQL by performing filtering, sorting, grouping, joins, aggregate functions, subqueries, views, and indexing.
