# SQL-Project-2-Customer-Orders-and-Product-Performance

A fictional shop dataset that grows the earlier single-table sales exercises into a relational database. The project includes customers, orders, products, and order items, with purchase-time prices and order statuses.

Business questions
What was in each non-cancelled order, and how much revenue did each line generate?
Which orders and customers generated the most revenue?
Which categories and products performed best?
How did revenue change month to month?
How can a report include customers who have not made an eligible purchase?
SQL skills
Primary and foreign keys, CHECK constraints, multi-table JOINs, LEFT JOIN, conditional aggregation, COALESCE, common table expressions, date grouping, RANK() and LAG() window functions.

Run it
Open order_analysis.sql in a SQLite client and run the whole file. The script drops and recreates only its four project tables, inserts fictional sample data, then runs eight analyses. SQLite foreign key enforcement is enabled in the script.

Reporting choices
Revenue reports count completed and shipped orders and exclude cancelled orders. sale_price is stored on each order item to preserve the price paid at purchase time if the product catalog price changes later. All data is fictional.

If anything else goes wrong, make sure to contact me.

SAT
