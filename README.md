# online-bookstore-sql-analysis

📖 *Project Overview*
This project demonstrates advanced SQL analytics using PostgreSQL by designing and analyzing a relational database for an online bookstore.
The objective was to simulate real-world business scenarios and extract actionable insights from transactional data using structured query techniques.
The database consists of three datasets:
Books
Customers
Orders
By applying advanced SQL concepts, this project transforms raw data into meaningful business intelligence that supports performance tracking and decision-making.

🛠 Tools & Technologies
PostgreSQL
pgAdmin 4
SQL (Advanced Queries)
Git & GitHub
🗄 Database Schema Design
The relational database was designed with proper normalization and referential integrity:
1️⃣ Books
Stores product-level information including genre, price, and stock availability.
2️⃣ Customers
Contains customer demographic and geographic data.
3️⃣ Orders
Captures transactional records linking customers and books through foreign key relationships.
Primary and foreign key constraints were implemented to maintain data consistency and relational structure.


📊 Business Problems Solved
This project answers key business questions such as:
Who are the highest revenue-generating customers?
Which book genres drive the most sales?
What are the monthly revenue trends?
Which books are understocked relative to demand?
How does purchasing behavior vary by region?
Which authors generate the highest sales volume?


📈 Advanced SQL Concepts Applied
JOIN operations across multiple tables
GROUP BY and HAVING clauses
Aggregate functions (SUM, AVG, COUNT)
Common Table Expressions (CTEs)
Window Functions (RANK, SUM OVER)
Customer segmentation using CASE statements
Revenue trend analysis using DATE_TRUNC
Inventory tracking using LEFT JOIN and COALESCE
Query optimization concepts (indexing awareness)


🔎 Sample Analytical Insights
✔ Identified top-spending customers using ranking functions
✔ Segmented customers into High, Medium, and Low value categories
✔ Analyzed monthly revenue performance trends
✔ Determined most frequently ordered books
✔ Calculated remaining stock after order fulfillment
✔ Evaluated sales distribution by genre and author


💼 Business Value
This project demonstrates the ability to:
Design structured relational databases
Translate business questions into SQL queries
Extract KPIs from transactional datasets
Perform customer and revenue analysis
Apply analytical thinking to real-world data problems
SQL is not just about querying data — it is about generating actionable insights that drive informed business decisions.


🚀 Future Enhancements
Add indexing for performance optimization
Build materialized views for reporting
Integrate Power BI or Tableau dashboard
Implement stored procedures for automation
Add advanced analytics such as customer lifetime value (CLV) calculation


👩‍💻 Author
[Eshita Chakroborty]
Aspiring Business Analyst | SQL | Data Analytics
