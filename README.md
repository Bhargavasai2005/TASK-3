Files:
setup_ecommerce_db.sql: SQL script to create and populate the e-commerce database with tables Customers, Orders, Products, and Order_Items using the provided CSV data.
ecommerce_queries.sql: SQL queries addressing all task requirements, including filtering, grouping, joining tables, subqueries, aggregation, views, and optimized queries.
screenshots/: Folder containing screenshots of query outputs from SQLiteOnline.com.
README.md: This file, explaining the project and approach.
Approach
Database Setup:
Created an e-commerce database with tables Customers, Orders, Products, and Order_Items using the provided CSV files (customers.csv, orders.csv, products.csv, order_items.csv).
Defined relationships with foreign keys and added indexes on customer_id, order_id, and product_id for optimization.
SQL Queries:
Wrote 9 queries to meet all requirements:
Filtered products by price with WHERE and sorted with ORDER BY
Grouped data to calculate quantities with GROUP BY.
Used INNER, LEFT, and emulated RIGHT JOINs to combine tables.
Applied subqueries to filter products based on order status.
Used SUM and AVG for revenue and order value calculations.
Created a view (OrderSummary) for aggregated order data and queried it.
Leveraged indexes for faster query execution.
Execution:
Used SQLiteOnline.com in SQLite mode to import the database and run queries.
Captured screenshots of query outputs for validation.
Documentation:
Organized all files and screenshots in this repository for submission.
Tools Used
SQLiteOnline.com: Online SQL editor for creating the database, running queries, and capturing outputs.
SQLite: Database engine used for its simplicity and compatibility with the task requirements.
GitHub: For hosting and submitting the solution.
How to Run
Import Database:
Open SQLiteOnline.com and select "SQLite" mode.
Copy the contents of setup_ecommerce_db.sql into the editor and click "Run" to create and populate the database.
Alternatively, import the database file if saved locally (ecommerce.db).
Execute Queries:
Copy the queries from ecommerce_queries.sql into the editor.
Run each query individually and view the results.
View Outputs:
Compare the results with the screenshots in the screenshots/ folder.

Screenshots
screenshots/query1_output.png: Output for filtering products by price.
screenshots/query2_output.png: Output for INNER JOIN showing order details.
screenshots/query3_output.png: Output for LEFT JOIN listing customers and orders.
screenshots/query4_output.png: Output for emulated RIGHT JOIN.
screenshots/query5_output.png: Output for subquery filtering products.
screenshots/query6_output.png: Output for aggregate functions (SUM, AVG).
screenshots/query8_output.png: Output for querying the OrderSummary view.
screenshots/query9_output.png: Output for optimized query using an index.
