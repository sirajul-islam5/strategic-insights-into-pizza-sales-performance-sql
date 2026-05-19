# Strategic Insights into Pizza Sales Performance - SQL 

A SQL-based data analysis project exploring pizza order patterns, revenue trends, and customer preferences to generate actionable business insights.

---

## Project Overview

This project analyzes a pizza restaurant's sales database to answer 13 business questions covering order volume, revenue, popular items, size preferences, and time-based ordering patterns. The goal was to extract meaningful insights that can support decisions around menu planning, staffing, and promotional strategies.

---

## Tools Used

- MySQL Workbench
- SQL (Joins, Subqueries, Aggregate Functions, Window Functions)

---

## Database Structure

The analysis is based on four relational tables:

- `orders` — order_id, order_date, order_time
- `order_details` — order_details_id, order_id, pizza_id, quantity
- `pizzas` — pizza_id, pizza_type_id, size, price
- `pizza_types` — pizza_type_id, name, category, ingredients

---

## Business Questions Answered

### Basic
1. Retrieve the total number of orders placed
2. Calculate the total revenue generated from pizza sales
3. Identify the highest-priced pizza
4. Identify the most common pizza size ordered
5. List the top 5 most ordered pizza types along with their quantities

### Intermediate
6. Find the total quantity of each pizza category ordered
7. Determine the distribution of orders by hour of the day
8. Find the category-wise distribution of pizzas
9. Calculate the average number of pizzas ordered per day

### Advanced
10. Determine the top 3 most ordered pizza types based on revenue
11. Calculate the percentage contribution of each pizza type to total revenue
12. Analyze the cumulative revenue generated over time
13. Determine the top 3 most ordered pizza types based on revenue for each pizza category

---

## Key Findings

- **Total Orders:** 21,350
- **Total Revenue:** $817,860.05
- **Highest-Priced Pizza:** The Greek Pizza at $35.95
- **Most Popular Size:** Large (18,526 orders)
- **Top Pizza by Quantity:** The Classic Deluxe Pizza (2,453 units)
- **Peak Ordering Hours:** 12:00–13:00 and 17:00–18:00
- **Top Revenue Category:** Classic (26.91%), followed by Supreme (25.46%)

---

## Business Insights

Classic and Supreme pizzas are clear customer favorites — they consistently top both order volume and revenue, making them the categories worth promoting most. Orders spike heavily around noon and again in the early evening, which means having the right staff and stock ready during those hours can make a real difference in service. Since Large is by far the most popular size, creating meal deals or combo offers around it could be a simple but effective way to increase the average spend per order.

---

## Acknowledgement

This project was completed with guided instruction from an experienced instructor. I followed the instructor's walkthrough, then ran, adapted, and validated each query independently. All executed results and presentation slides reflect my own work.

---


**Md. Sirajul Islam**  
- GitHub: [@sirajul-islam5](https://github.com/sirajul-islam5) 
