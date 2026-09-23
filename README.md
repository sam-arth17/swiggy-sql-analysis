# Swiggy SQL Analysis

A MySQL data analysis case study exploring customer behavior, restaurant performance, revenue and delivery operations using a Swiggy style relational database.

## Project Overview

This project analyzes a relational food delivery database containing customers, restaurants, orders, payments, delivery partners and order-delivery mappings.

The analysis uses SQL to explore customer ordering patterns, restaurant revenue and ratings, delivery partner activity and relationships across multiple tables.

## Database Structure

The database consists of:

- `customers` — Customer profiles and city information
- `restaurants` — Restaurant details and ratings
- `orders` — Order transactions
- `payment` — Payment amounts associated with orders
- `deliverypartners` — Delivery partner information
- `orderdelivery` — Mapping between orders and delivery partners

## SQL Techniques Used

- Filtering and sorting with `WHERE`, `ORDER BY`, and `LIMIT`
- Aggregation using `COUNT`, `SUM`, and `AVG`
- Group-level filtering with `HAVING`
- `INNER JOIN` and `LEFT JOIN`
- Subqueries
- Self joins
- Date functions such as `DATE_ADD` and `MAX`
- `DISTINCT`
- Multi table relational analysis

## Analysis Areas

### Customer Behaviour
- Customer ordering activity
- Customers with no orders
- Order frequency by customer
- Ordering activity across cities
- Customers ordering on multiple distinct days

### Restaurant & Revenue Analysis
- Restaurant level revenue
- Restaurant ratings
- Highest rated restaurants
- Relationships between orders, restaurants and payments

### Delivery Analysis
- Delivery partner activity
- Delivery volume
- Number of distinct customers served by delivery partners

### Advanced Relational Analysis
- Identified customer pairs in the same city who ordered from the same restaurant on different dates using multi table joins and self-join logic.

## Key Insights

- Delhi and Mumbai showed notable concentrations of repeat customer activity.
- Restaurant revenue varied substantially across the dataset, ranging from ₹0 to more than ₹2,700.
- A smaller group of customers showed frequent ordering activity across multiple days.
- Delivery partner activity varied by both number of deliveries and number of distinct customers served.

## Project Files

- `swiggy_analysis.sql` — Cleaned SQL queries used for the analysis
- `Swiggy_SQL_Case_Study.pdf` — Project documentation containing query results and analysis

## Author

**Samarth Pathak**

[LinkedIn](https://linkedin.com/in/samarth-pathak-5680692b9) · [GitHub](https://github.com/sam-arth17)
