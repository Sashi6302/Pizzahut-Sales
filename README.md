# Pizza Sales Data Analysis

This project involves analyzing a pizza sales dataset using MySQL to derive meaningful insights and answer specific business-related questions. The analysis is categorized into **Basic**, **Intermediate**, and **Advanced** levels based on complexity.

---

## Problem Statement
The dataset comprises four tables:
- **`order_details`**
- **`orders`**
- **`pizza_types`**
- **`pizzas`**

The goal is to analyze these tables and extract insights into sales patterns, revenue generation, and ordering trends.

---

## Tasks and Insights

### Basic Analysis
- Retrieve the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Identify the most common pizza size ordered.
- List the top 5 most ordered pizza types along with their quantities.

### Intermediate Analysis
- Join the necessary tables to find the total quantity of each pizza category ordered.
- Determine the distribution of orders by hour of the day.
- Analyze the category-wise distribution of pizzas by joining relevant tables.
- Group the orders by date and calculate the average number of pizzas ordered per day.
- Determine the top 3 most ordered pizza types based on revenue.

### Advanced Analysis
- Calculate the percentage contribution of each pizza type to total revenue.
- Analyze the cumulative revenue generated over time.
- Determine the top 3 most ordered pizza types based on revenue for each pizza category.

---

## Dataset Overview

### Table Descriptions
1. **`order_details`**: Contains details of each order including order ID, pizza ID, quantity, and price.
2. **`orders`**: Includes metadata about orders such as order ID, date, and time.
3. **`pizza_types`**: Details about different pizza types, including category and description.
4. **`pizzas`**: Contains information about pizzas, including size, type, and price.

---

## SQL Techniques Used
- **Joins**: Combining relevant tables for comprehensive analysis.
- **Aggregations**: Calculating totals, averages, and percentages.
- **Grouping**: Analyzing trends over time and categories.
- **Subqueries**: For complex computations.
- **Window Functions**: Used for cumulative revenue analysis and ranking.
