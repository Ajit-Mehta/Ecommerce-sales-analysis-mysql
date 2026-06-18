# E-Commerce Sales Analysis (MySQL Project)

## Project Overview
This project is a MySQL-based E-Commerce Sales Analysis system designed to analyze sales performance, customer behavior, and product trends.

The goal is to extract meaningful business insights from raw transactional data using SQL queries.

## Tools Used
- MySQL
- SQL (Joins, Group By, Window Functions)
- GitHub

## Key Insights
- Identified top customers based on total spending
- Analyzed monthly sales trends
- Found best-selling products
- Performed city-wise sales analysis
- Calculated revenue and order performance

- ## Tables Used
- customers
- products
- orders
- order_details
- payments

- ## Sample SQL Query

SELECT 
    customer_id,
    SUM(order_amount) AS total_spent
FROM orders
GROUP BY customer_id
ORDER BY total_spent DESC;

## Author
Ajit Kumar  
Aspiring Data Analyst
Skills: SQL | Power BI | Tableau
