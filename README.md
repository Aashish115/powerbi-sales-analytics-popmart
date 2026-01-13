# powerbi-sales-analytics-popmart
Power BI dashboard --- sales + operations insights (2025)

# Power BI Sales Analytics Dashboard – Popmart Case Study

## Overview
This project presents a comprehensive **Sales Analytics and Business Intelligence dashboard** developed using **Microsoft Power BI**. The analysis is based on a multi-table retail dataset simulating Popmart’s global sales operations. The objective of this project is to transform raw transactional data into actionable business insights through effective data modeling, DAX calculations, and interactive visualizations.

This project was developed as part of **ICT761 – Business Analytics and Business Intelligence**, demonstrating end-to-end analytical skills from data preparation to insight-driven decision support.

---

## Dataset & Data Model
The dataset consists of multiple related tables:
- `popmart_orders` – Order-level transactional data
- `popmart_order_items` – Line-item sales details
- `popmart_products` – Product and collection metadata
- `popmart_stores` – Store and city information
- `dim_customers` – Customer demographics
- `DateTable` – Custom calendar table for time intelligence

A **star schema–oriented data model** was designed with proper relationships to ensure optimized filtering, aggregation, and performance.

---

## Data Preparation & DAX
Key data preparation and analytical steps include:
- Creation of a dedicated Date table for time-based analysis
- Development of DAX measures such as:
  - Completed Revenue
  - Completed Orders
  - Average Order Value (AOV)
  - Completion Rate (%)
  - Cancelled and Returned Orders
- Handling of order status logic to distinguish completed vs non-completed transactions

This ensures clean, consistent, and reliable metrics across all visuals.

---

## Dashboard Structure

### 1. Executive Overview
- KPI Cards for Completed Revenue, Completed Orders, and AOV
- Monthly revenue trend analysis
- Top-performing product collections
- Interactive slicers for time period, city, and product collection

Purpose: Provide senior stakeholders with a high-level performance snapshot and trend awareness.

---

### 2. Sales & Operations Analysis
- Completion rate, cancelled orders, and returned orders
- Orders by purchase channel (Store, Online, Event Booth)
- Completed revenue by store city
- Diagnostic insights into revenue leakage and operational inefficiencies

Purpose: Identify fulfilment bottlenecks and conversion opportunities.

---

### 3. Advanced Analytics (Scatter & Heat Map)
- Scatter plot: Average Order Value vs Total Quantity by product collection
- Heat map (matrix with conditional formatting): Revenue concentration by city and product collection
- Outlier detection and performance clustering
- Geographic and product-level demand concentration analysis

Purpose: Enable exploratory and diagnostic analytics beyond descriptive reporting.

---

## Key Insights
- Revenue is driven primarily by order volume rather than high ticket size.
- Completion rate (~25%) indicates significant revenue leakage due to cancellations and returns.
- Demand is evenly distributed across channels, but operational inefficiencies constrain realized revenue.
- A small number of product collections account for a disproportionate share of revenue.
- Scatter and heat map analysis reveal strong product–market fit for select collections and geographic dependencies.
- Even marginal improvements in completion rate could yield substantial revenue uplift without increasing demand.

---

## Tools & Technologies
- Microsoft Power BI
- DAX
- Data modeling (Star schema)
- Interactive dashboards and slicers
- Advanced visualization techniques (scatter plots, heat maps)

---

## Author
**Aashish Bhandari**  
Bachelor / Master of Information Technology  
Aspiring Business Analyst / Data Analyst  

---

## Repository Contents
- Power BI implementation file (.pbix)
- Dashboard screenshots
- Data model diagram
- Documentation and insights
