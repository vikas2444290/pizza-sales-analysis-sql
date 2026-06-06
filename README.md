# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview

This project analyzes one year of pizza sales data using SQL to uncover customer purchasing behavior, revenue trends, product performance, and operational insights.

The analysis was performed on a relational database consisting of four interconnected tables containing order information, pizza details, pricing information, and pizza categories.

---

## 🎯 Objectives

* Analyze overall sales performance.
* Identify customer purchasing preferences.
* Determine top-performing pizzas and categories.
* Discover peak ordering hours.
* Generate actionable business recommendations using SQL-driven insights.

---

## 🗂 Dataset Information

The dataset consists of four relational tables:

### Orders

Contains order-level information.

| Column   |
| -------- |
| order_id |
| date     |
| time     |

### Order Details

Contains individual pizza items within each order.

| Column           |
| ---------------- |
| order_details_id |
| order_id         |
| pizza_id         |
| quantity         |

### Pizzas

Contains pizza sizes and pricing information.

| Column        |
| ------------- |
| pizza_id      |
| pizza_type_id |
| size          |
| price         |

### Pizza Types

Contains pizza names, categories, and ingredients.

| Column        |
| ------------- |
| pizza_type_id |
| name          |
| category      |
| ingredients   |

---

## 📊 Dataset Summary

| Metric              | Value   |
| ------------------- | ------- |
| Total Orders        | 21,350  |
| Total Pizzas Sold   | 49,574  |
| Total Revenue       | 817,860 |
| Average Daily Sales | 138     |
| Pizza Categories    | 4       |
| Pizza Types         | 32      |

---

## 🛠 SQL Concepts Used

* Joins
* Aggregate Functions
* GROUP BY
* ORDER BY
* Subqueries
* Window Functions
* Ranking Functions
* Revenue Analysis

---

## 🔍 Business Questions Answered

1. Retrieve the total number of orders placed.
2. Calculate total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Determine the most common pizza size ordered.
5. List the top 5 most ordered pizza types.
6. Find the total quantity sold by category.
7. Analyze order distribution by hour.
8. Determine category-wise pizza distribution.
9. Calculate average pizzas ordered per day.
10. Identify the top 3 pizzas based on revenue.
11. Calculate category revenue contribution.
12. Analyze cumulative revenue over time.
13. Identify the top revenue-generating pizzas within each category.

---

## 📈 Key Insights

* The restaurant processed 21,350 orders during the year.
* Total revenue exceeded 817,860.
* Large-sized pizzas were the most preferred choice.
* The Classic Deluxe Pizza was the most frequently ordered pizza.
* Classic pizzas recorded the highest sales volume.
* Customer demand peaked during lunch and evening hours.
* Thai Chicken Pizza generated the highest revenue among all pizza types.

---

## 💡 Business Recommendations

* Increase inventory planning for Large-sized pizzas.
* Promote top-performing pizzas through combo offers.
* Focus marketing efforts on the Classic category.
* Schedule additional staff during peak demand periods.
* Bundle lower-performing pizzas with popular products.

---

## 📁 Repository Structure

```text
pizza-sales-analysis-sql
│
├── Dataset
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── SQL Queries
│   └── pizza_sales_analysis.sql
│
├── Presentation
│   └── Pizza Sales Analysis.pdf
│
├── Images
│   ├── project_cover.png
│   └── database_schema.png
│
└── README.md
```

---

## 📎 Project Files

* Dataset Files
* SQL Query Script
* Project Presentation
* Documentation

---

## 👨‍💻 Author

**Vikas Yadav**
