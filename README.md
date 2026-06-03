# Pizza-Sales-Analysis
Overview
The project is a MySQL-based data analysis of pizza sales, working with 21,000+ records. It demonstrates relational database design with proper primary/foreign key relationships and CSV data ingestion.

data set : https://www.kaggle.com/datasets/ylenialongo/pizza-sales 

Database Schema

Four tables are used: orders, order_details, pizzas, and pizza_types, joined together for various analyses.
SQL Queries Covered
The project answers a series of business questions across three difficulty tiers:

Basic

Total number of orders placed
Total revenue from pizza sales
Highest-priced pizza
Most common pizza size ordered
Top 5 most ordered pizza types by quantity

Intermediate

Total quantity ordered per pizza category (Classic, Veggie, Chicken, Supreme)
Order distribution by hour of day
Category-wise pizza count
Average pizzas ordered per day

Advanced

Top 3 pizza types by revenue
Percentage revenue contribution by pizza category (using a subquery for the total)

Notable Techniques

Multi-table JOINs across 3 tables in a single query
Subqueries for percentage calculations
Aggregations with SUM, COUNT, AVG, ROUND
GROUP BY + ORDER BY for ranked results
HOUR() function for time-based analysis

What's in the repo

pizza_sales_sql_query.sql — all the analysis queries
pizza sales Questions.txt — the business questions being answered
pizza-sales.pptx — a presentation of the findings
