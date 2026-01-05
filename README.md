Amazon Brazil E‑Commerce SQL Analytics Project
Project Overview

This project focuses on end‑to‑end SQL‑based data analysis using an Amazon Brazil e‑commerce dataset. The objective is to derive meaningful business insights related to payments, customers, products, sales trends, and customer segmentation. The project demonstrates strong command over SQL concepts such as schema design, joins, aggregations, subqueries, CTEs, window functions, and analytical reporting.

The project is designed to simulate real‑world analytics use cases relevant to roles such as Data Analyst, Data Engineer, and Business Intelligence Analyst.

Tech Stack

Database: PostgreSQL

Language: SQL

Tools: pgAdmin / Any SQL Client, Excel (for visualization)

Database Design

A dedicated database and schema were created to organize the data efficiently.

Schema

amazon_brazil

Tables Created

customers – Customer identification and location data

orders – Order lifecycle and timestamps

order_items – Product‑level order details with pricing

payments – Payment methods and transaction values

product – Product attributes and category details

seller – Seller information

All tables were created using appropriate data types and primary keys to reflect a production‑like schema.

Key Business Analyses
Analysis 1: Payment & Pricing Insights

Standardized average payment values by payment type

Calculated percentage distribution of orders by payment method

Identified smart products within a specific price range

Determined top‑performing sales months

Analyzed product categories with high price variation

Measured payment consistency using standard deviation

Detected incomplete or invalid product category names

Analysis 2: Customer & Product Performance

Segmented orders into low, medium, and high value ranges

Calculated min, max, and average prices by product category

Identified repeat customers

Classified customers as New, Returning, or Loyal using a temporary table

Identified top revenue‑generating product categories

Analysis 3: Advanced Analytics & Trends

Seasonal sales analysis using subqueries

Identified products with above‑average sales volume

Monthly revenue trend analysis (exported to Excel for visualization)

Customer segmentation using CTEs

Ranked high‑value customers using window functions

Calculated cumulative monthly sales per product

Computed month‑over‑month sales growth by payment type

Advanced SQL Concepts Used

Joins (INNER JOIN)

Aggregate Functions (SUM, AVG, MIN, MAX, COUNT)

Window Functions (RANK, LAG)

Common Table Expressions (CTEs)

Temporary Tables

Subqueries

Date & Time Functions

Case Statements

Business Value

Helps understand customer behavior and loyalty patterns

Identifies high‑revenue product categories

Improves payment strategy through consistency analysis

Enables seasonal and monthly sales forecasting

Supports targeted marketing and reward programs

How to Use This Project

Clone the repository from GitHub

Create the database and schema

Run table creation scripts

Execute analysis queries sequentially

Export selected outputs to Excel for visualization

Resume‑Ready Project Description

Amazon Brazil E‑Commerce SQL Analytics Project

Designed and implemented a complete relational database schema using PostgreSQL

Performed 20+ real‑world business analyses using advanced SQL

Applied CTEs, window functions, and subqueries for customer segmentation and trend analysis

Built payment, product, and seasonal sales insights to support business decision‑making

Delivered analytics outputs suitable for dashboards and executive reporting

Future Enhancements

Add indexes for performance optimization

Build Power BI / Tableau dashboards

Automate data ingestion pipelines

Convert analysis into stored procedures
