# Power BI Project: Supply Chain Service Level Analysis – AtliQ Mart

This Power BI project analyzes and tracks the delivery performance of **AtliQ Mart**, a fast-growing FMCG manufacturer in India. The report focuses on key service-level metrics such as **On-Time Delivery**, **In-Full Delivery**, and **On-Time In-Full (OTIF)** to address customer satisfaction issues and improve supply chain efficiency.

---

## About the Business

**AtliQ Mart** is a growing FMCG manufacturer headquartered in **Gujarat, India**, currently operating in **Surat, Ahmedabad, and Vadodara**. With plans to expand to metro/Tier-1 cities within the next 2 years, the company is focusing on improving service reliability.

Recently, several key customers did not renew their annual contracts, citing **poor service delivery**—especially issues with **late or incomplete deliveries**. The management has tasked the **Supply Chain Analytics** team with identifying and resolving these issues using daily performance tracking.

---

## Project Objective

The objective of this project is to help AtliQ Mart:

- Monitor daily delivery performance for all customers
- Detect patterns of delayed or incomplete orders
- Measure key delivery service metrics
- Compare performance against customer-specific service level targets
- Take proactive actions to prevent further customer churn

---

## Data Overview

The project uses simulated operational datasets representing:

- **Sales Orders** with delivery status and dates
- **Target Service Levels** set per customer
- **Product and Customer Master Data**

Each record includes:
- Order Date, Delivery Date
- Quantity Ordered vs Delivered
- Expected vs Actual Delivery Time
- Customer ID, Product ID

---

## Key Metrics Tracked

- **On-Time Delivery % (OT%)**
  > Measures the percentage of orders delivered on or before the committed date

- **In-Full Delivery % (IF%)**
  > Measures the percentage of orders delivered completely with no missing items

-  **On-Time In-Full % (OTIF%)**
  > Combined measure of both timeliness and completeness of orders

Each metric is tracked **daily per customer** and compared to a **target threshold** (e.g., 95%).

---

## Dashboard Features

This Power BI report includes:

- **Daily Delivery Performance Tracker**
- **Trend Analysis of OT, IF, and OTIF over time**
- **Customer-Level Service Insights**
- **Low-Performance Alerts & Filters**
- **Service Level Comparison vs Target**

Users can filter by:
- City
- Customer
- Product Category
- Date Range

---

## Tools & Technologies

- **Power BI Desktop**
- **Power Query for Data Transformation**
- **DAX for Custom KPIs and Measures**
- **Excel/CSV Data Sources**

---

## Business Insights Enabled

- Early identification of service lapses
- Improved communication with logistics and suppliers
- Data-driven root cause analysis for customer issues
- Better forecasting of delivery bottlenecks

---

## Getting Started

1. Clone the repo:
   ```bash
   https://github.com/arpanmk/Supply-Chain-analysis
