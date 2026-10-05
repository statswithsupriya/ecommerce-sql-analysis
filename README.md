# E-Commerce Marketplace Analytics Using SQL
End-to-end SQL analysis of Olist E-Commerce dataset covering customer, seller, product and revenue insights.

## Project Overview

Performed end-to-end analytical exploration of the Olist E-Commerce dataset using SQL. The objective of this project was to analyze customer behavior, seller performance, product performance, revenue trends, retention patterns, and overall business performance through structured SQL analysis.

The project focused not only on answering business questions but also on validating data quality and ensuring analytical reliability through Data Quality Assessment (DQA).

---

## Tools & Technologies

- SQL
- DuckDB
- Data Analysis
- Business Analytics
- Statistical Thinking

---

## Dataset Overview

The Olist E-Commerce dataset contains information related to:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Category Translation

Dataset Scale:

- 100K+ Orders
- 96K+ Customers
- 3K+ Sellers
- Multiple Product Categories

---

## Project Objectives

- Validate data quality before analysis.
- Understand customer purchasing behavior.
- Identify top-performing sellers.
- Evaluate product performance.
- Analyze revenue trends.
- Study repeat purchasing behavior.
- Identify revenue concentration patterns.
- Generate business insights and recommendations.

---

# Data Quality Assessment (DQA)

Before performing analysis, a comprehensive data quality assessment was conducted.

### Data Quality Checks Performed

#### Missing Value Analysis

- Identified null and missing values across multiple tables.
- Evaluated impact of missing product category information.

#### Duplicate Detection

- Checked for duplicate primary keys.
- Validated uniqueness constraints.

#### Referential Integrity Validation

Verified relationships between:

- Customers and Orders
- Orders and Order_Items
- Products and Order_Items
- Sellers and Order_Items

#### Key Validation

Validated:

- customer_id
- order_id
- product_id
- seller_id

to ensure data reliability.

---

# Customer Analysis

Business Questions Answered:

### Customer Distribution

- How many customers exist?
- Which states have the highest customer concentration?

### Repeat Customer Analysis

- How many customers made repeat purchases?
- Which customers generated maximum revenue?

### Customer Segmentation

Used:

- NTILE()
- Window Functions

to segment customers based on purchasing patterns.

### Customer Revenue Contribution

Analyzed:

- Top Customers
- Customer Revenue Ranking
- Customer Purchase Frequency

---

# Seller Analysis

Business Questions Answered:

### Top Sellers

- Which sellers generate maximum revenue?
- Which sellers process the highest number of orders?

### Seller Ranking

Implemented:

- RANK()
- DENSE_RANK()
- ROW_NUMBER()

to rank seller performance.

### Revenue Contribution Analysis

Identified:

- High revenue sellers
- High volume sellers
- Revenue concentration among sellers

---

# Product Analysis

Business Questions Answered:

### Product Performance

- Which products generate maximum revenue?
- Which categories perform best?

### Category Analysis

Studied:

- Top Revenue Categories
- Revenue Share by Category
- Category Contribution Analysis

### Pareto Analysis

Applied Pareto principles to identify:

- Categories driving majority revenue
- Revenue concentration among products

---

# Revenue Analysis

Business Questions Answered:

### Total Revenue Analysis

Calculated:

- Total Revenue
- Revenue Trends
- Revenue Distribution

### Running Totals

Implemented:

- Running Revenue Calculations

using Window Functions.

### Revenue Ranking

Ranked:

- Customers
- Products
- Sellers

based on revenue contribution.

---

# Advanced SQL Concepts Used

### Joins

- Inner Join
- Left Join

### Common Table Expressions (CTEs)

Used to simplify complex analytical queries.

### Window Functions

Implemented:

- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- NTILE()
- LAG()
- LEAD()

### Aggregations

Used:

- SUM()
- AVG()
- COUNT()
- MAX()
- MIN()

### Conditional Logic

Implemented:

- CASE WHEN

### Subqueries

Used for nested business analysis requirements.

---

# Key Business Insights

- A small proportion of sellers contributed a significant share of revenue.
- Revenue generation was concentrated among a limited set of product categories.
- Customer purchasing behavior showed varying levels of engagement and repeat purchasing.
- Certain states contributed disproportionately to overall business revenue.
- Top-performing products and sellers accounted for a significant share of total revenue.
- Data quality validation improved confidence in analytical findings.

---

# Skills Demonstrated

## SQL

- Joins
- CTEs
- Window Functions
- Aggregations
- Subqueries
- Ranking Functions
- Conditional Logic

## Analytics

- Data Quality Assessment
- Revenue Analysis
- Customer Analysis
- Seller Analysis
- Product Analysis
- Segmentation Analysis
- Pareto Analysis

## Business Intelligence

- KPI Analysis
- Performance Analysis
- Trend Analysis
- Revenue Concentration Analysis

---

# Key Learning Outcomes

- Developed a structured approach to Data Quality Assessment.
- Learned to validate analytical assumptions before reporting.
- Applied advanced SQL concepts to solve business problems.
- Performed end-to-end customer, seller, product, and revenue analysis.
- Improved understanding of ranking, segmentation, and revenue concentration techniques.
- Generated actionable business insights using analytical SQL.

---

# Project Outcome

Successfully developed an end-to-end SQL analytics project capable of validating data quality, analyzing business performance, identifying revenue drivers, evaluating customer behavior, and generating actionable business insights using advanced SQL techniques.
