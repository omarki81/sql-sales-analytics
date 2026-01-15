📊 SQL Sales Analytics Project (PostgreSQL + Power BI)
📌 Project Overview

This project demonstrates an end-to-end Business Analytics workflow using PostgreSQL and Power BI.
I designed a relational database, populated it with realistic sales data, wrote business-oriented SQL queries, and created SQL views that can be directly consumed by Power BI dashboards.

The objective is to analyze sales performance, customer behavior, and product profitability, similar to real-world analytics tasks in companies.

🧠 Business Questions Answered

What is the total revenue and profit?

How does monthly revenue evolve over time?

Who are the top customers by revenue?

Which products and categories generate the highest profit?

How can customers be segmented by value?

🗄️ Database Schema

The database is designed using a normalized relational model:

customers → customer information

products → product catalog and costs

orders → customer orders

order_items → sales fact table

payments → payment details

This structure follows best practices used in analytics and BI projects.

🛠️ Tools & Technologies

PostgreSQL – database & SQL analytics

pgAdmin – database management

Power BI – data visualization & dashboards

SQL – joins, aggregations, CTEs, window functions, views

📈 SQL Analytics & Techniques Used

Complex JOINs across multiple tables

Aggregations (SUM, COUNT, AVG)

CTEs (WITH) for readable analytics logic

Window functions (RANK, LAG)

CASE WHEN for business segmentation

SQL Views for reusable analytics layers

📂 Project Structure
sql-sales-analytics/
│
├── README.md
├── schema.sql          -- Database schema creation
├── insert_data.sql     -- Realistic sample data
├── views.sql           -- Analytics views for BI
├── queries.sql         -- Business analytics queries
└── powerbi/
    └── sales_dashboard.pbix

🔗 Power BI Integration

SQL views were created to serve as clean data sources for Power BI:

vw_sales

vw_monthly_revenue

vw_customer_performance

vw_product_performance

This separation ensures:

Business logic handled in SQL

Visualization handled in Power BI

🎯 Key Learning Outcomes

Designing analytics-ready relational databases

Writing SQL for real business decision-making

Building reusable SQL layers for BI tools

Translating raw data into actionable insights

👤 Author

Omar Gharbi
Business student focused on Business Analytics & Data Analysis
Skills: SQL • PostgreSQL • Power BI • Excel
🎯 Aspiring  Business Analyst / Data Analyst
