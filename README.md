# 🍕 Domino’s Pizza Sales Analysis (SQL Project)

## 📌 Project Summary

This project explores Domino’s pizza sales data using SQL to extract meaningful insights related to customer demand, product performance, and revenue trends. The analysis is performed on a structured relational dataset, focusing on solving real business-driven questions through efficient querying.

## 🗂️ Dataset Structure

The project is built on four interconnected tables:

* **orders** → stores order date and time
* **order_details** → contains quantity and pizza IDs
* **pizzas** → includes size and pricing details
* **pizza_types** → provides category and name of pizzas

## ⚙️ Tools & Technologies

* MySQL
* SQL (Joins, Aggregations, Window Functions, Views, CTEs)

## 🧠 Concepts Applied

* Multi-table joins for relational analysis
* Aggregation functions for metrics calculation
* Window functions for ranking and cumulative trends
* Views and CTEs for modular query building
* Revenue and percentage-based analysis

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

* Larger pizza sizes show higher demand, indicating group ordering behavior
* Certain categories dominate overall sales volume
* A small set of pizzas contributes significantly to total revenue
* Orders peak during lunch and evening hours
* Revenue shows a steady upward trend over time
* Premium pizzas generate higher revenue despite lower frequency

## 💰 Revenue Analysis

Revenue is calculated using:

```
price × quantity
```

* Total revenue is aggregated across all orders
* Cumulative revenue is analyzed using window functions over time

## 📁 Project Structure

```
Dominos-SQL-Sales-Analysis/
│
├── dominos_analysis.sql
├── data/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
└── README.md
```

## 🚀 Conclusion

This project demonstrates how SQL can be used to analyze real-world business data by combining multiple tables, performing advanced calculations, and generating actionable insights. It highlights strong skills in data querying, transformation, and interpretation.
