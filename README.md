# Retail Orders SQL Analysis

A SQL project analyzing a retail orders dataset to answer common business questions — built while learning SQL fundamentals as a CSE student preparing for Data Analyst roles.

## Tools Used
- MySQL / MySQL Workbench

## Dataset
A single `orders` table with the following columns:
- `order_id`, `customer_name`, `product`, `category`, `quantity`, `price`, `city`

*(See `queries.sql` for the full table schema and sample data.)*

## Business Questions Answered
1. How many total orders were placed?
2. What is the total revenue generated?
3. What is the average order value?
4. Which product category sells the most by quantity?
5. Show orders from a specific city, sorted by price (highest first)
6. Which cities generate the highest total revenue? (using `HAVING`)
7. Which categories have more than 2 orders? (using `HAVING` + `COUNT`)
8. What are the top 3 highest-value orders? (using `LIMIT`)

## SQL Concepts Practiced
`CREATE TABLE` · `INSERT` · `SELECT` · `WHERE` · `ORDER BY` · `AND`/`OR` · Aggregate functions (`COUNT`, `SUM`, `AVG`, `MAX`, `MIN`) · `GROUP BY` · `HAVING` · `LIMIT`

## Key Insight Example
Filtering categories with more than 2 orders revealed that **Electronics** was the only category with significant order volume (3 orders), highlighting it as the dominant product line in this dataset.

## Next Steps
- Add a second table (e.g. `customers`) and practice SQL `JOIN`s
- Extend analysis using Python (pandas) for visualization
- Apply statistical concepts to deepen insights
