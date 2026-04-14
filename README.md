# 🍕 Domino’s Pizza Sales Analysis (SQL Project)

## 📌 Project Overview

This project analyzes Domino’s pizza sales data using SQL to uncover insights related to customer ordering patterns, product performance, and revenue trends. The goal is to transform raw transactional data into meaningful business insights using structured querying techniques.

## 🗂️ Dataset Description

The dataset is organized into four relational tables:

* **orders** – contains order date and time
* **order_details** – includes quantity and pizza IDs
* **pizzas** – stores size and pricing information
* **pizza_types** – defines pizza names and categories

## ⚙️ Tools & Technologies

* MySQL
* SQL (Joins, Aggregations, Window Functions, CTEs, Views)
* PowerPoint (for presentation)

## 🧠 SQL Concepts Used

* SELECT queries for data extraction
* INNER JOIN for combining multiple tables
* GROUP BY & ORDER BY for aggregation and sorting
* Aggregate functions (SUM, COUNT, AVG)
* Window functions (ROW_NUMBER, SUM OVER)
* CTEs and Views for structured analysis
* Revenue and percentage calculations

## ❓ Business Questions Solved

1. What is the total number of orders placed?
2. What are the top 5 most ordered pizza types?
3. What is the total quantity ordered per pizza category?
4. What is the category-wise distribution of pizzas?
5. What is the average number of pizzas ordered per day?
6a. What percentage does each pizza type contribute to total revenue?
6b. How does cumulative revenue grow over time?
7. What is the most commonly ordered pizza size?
8. Which pizza is the highest priced?
9. What is the total revenue generated?
10. What is the hourly distribution of orders?

## 📊 Key Insights

* Large-sized pizzas are the most preferred among customers
* A few categories contribute significantly to total sales volume
* Revenue follows a concentration pattern (majority from few items)
* Peak demand occurs during lunch and evening hours
* Sales show steady cumulative growth over time
* Premium pizzas generate higher revenue despite fewer orders

## 💰 Revenue Analysis

Revenue is calculated as:

```id="9shgqj"
price × quantity
```

* Total revenue is aggregated across all orders
* Cumulative revenue is computed using window functions

## 📁 Project Structure

```id="2qk8f0"
Dominos-SQL-Sales-Analysis/
│
├── data/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── Dominos Pizza Sales Analysis.sql
├── Dominos Pizza Sales Analysis.pptx
└── README.md
```

## 📊 Presentation

The project also includes a PowerPoint file showcasing key findings and insights derived from the SQL analysis.

## 🚀 Conclusion

This project highlights the ability to work with relational datasets, perform multi-table joins, and derive business insights using SQL. It demonstrates strong analytical thinking and practical data analysis skills applicable to real-world scenarios.
