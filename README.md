# Apple-Store-Analytics
Apple Store Analytics SQL Project – Designed a relational retail database system and performed advanced SQL analysis using joins, subqueries, aggregations, CTEs, and window functions to generate business insights on sales performance, pricing trends, and warranty claims.
📊 Apple Store Analytics – SQL Project
This project demonstrates the design and implementation of a relational retail database system using SQL. The database simulates real-world Apple store operations including product management, sales tracking, and warranty claim analysis.

🗂 Database Structure
The project includes 5 relational tables:
Stores – Store details (store_id as primary key)
Categories – Product categories (category_id auto-increment PK)
Products – Product name, category, launch date, price
Sales – Transaction records (store, product, quantity, date)
Warranty – Warranty claim details linked to sales
Primary and foreign key constraints ensure referential integrity.

🛠 SQL Concepts Used
INNER JOIN (multi-table analysis)
Subqueries (price comparison & filtering)
Aggregation Functions (SUM, COUNT, AVG)
GROUP BY
CTEs (Common Table Expressions)
Window Functions – DENSE_RANK()
ORDER BY with LIMIT (Top-N analysis)

📈 Key Business Analysis Performed
Store-wise total quantity sold
Products priced above average
Warranty claims grouped by repair status
Dense ranking of products within each category
Top 5 most expensive products
Identification of unsold inventory

🎯 Skills Demonstrated
Relational Database Design
Data Modeling & ER Diagram
Analytical SQL Query Writing
Business Insight Generation
Retail Data Analysis
