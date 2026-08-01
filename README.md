# Retail Merchandising & Inventory Intelligence Dashboard for In Your Shoe

## Project Overview

This project is an end-to-end **Retail Merchandising & Inventory Intelligence Dashboard** developed for **In Your Shoe**, a fashion retail brand.

Using **Microsoft Excel** for data preparation and **Power BI** for data modeling and visualization, the dashboard transforms raw retail data into actionable business insights that support merchandising, inventory planning, replenishment, markdown decisions, and inventory transfers.

The project follows a business intelligence workflow, from data cleaning and modeling to KPI development and executive reporting.

---

# Business Problem

Retail businesses constantly face inventory-related challenges that directly impact profitability and customer satisfaction.

Some products become overstocked and tie up working capital, while others run out of stock and lead to lost sales. Merchandising teams also need to identify slow-moving products before they become dead stock and ensure inventory is distributed efficiently across stores.

Without a centralized reporting solution, these decisions become reactive instead of data-driven.

This dashboard provides a single source of truth for monitoring inventory performance and supporting strategic merchandising decisions.

---

# Business Questions Answered

This dashboard was designed to answer four key business questions:

- Which products should be reordered?
- Which products should be discounted?
- Which products are becoming dead stock?
- Which stores need inventory transfers?

---

# Dashboard Pages

## 1. Executive Summary

The Executive Summary provides a high-level overview of business performance and inventory health, enabling executives to quickly understand the current state of the business.

### Key Insights

- Overall Revenue, Gross Profit and Units Sold
- Current Inventory Value
- Dead Stock Value
- Products at Stockout Risk
- Inventory Distribution by Stock Status
- Revenue Contribution by Category
- Inventory Investment by Category
- Monthly Revenue Trend
- Top Best-Selling Products
- Lowest-Selling Products

### Dashboard Preview

![Executive Summary](Images/1.%20Executive%20Summary.png)

---

## 2. Replenishment Analysis

This page helps merchandising and inventory planners identify products requiring replenishment before stockouts occur.

### Key Insights

- Products Below Reorder Point
- Total Reorder Quantity
- Products at Stockout Risk
- Inventory Value Below Reorder Point
- Reorder Quantity by Product Category
- Products Requiring Replenishment
- Stock Status Distribution
- Reorder Quantity by Store

### Dashboard Preview

![Replenishment Analysis](Images/2.%20Replenishment%20Analysis.png)

---

## 3. Markdown & Dead Stock

This page identifies products that require markdowns or close monitoring based on inventory health.

Products are dynamically classified as:

- Healthy
- At Risk
- Dead Stock

using business rules implemented in Power BI.

### Key Insights

- Dead Stock Products
- Dead Stock Value
- At Risk Products
- At Risk Inventory Value
- Slow Moving Products
- Inventory Health Distribution
- Dead Stock Value by Category
- Products Recommended for Markdown
- Product Status Distribution
- Inventory Condition by Category

### Dashboard Preview

![Markdown & Dead Stock](Images/3.%20Markdown%20%26%20Dead%20Stock.png)

---

## 4. Inventory Transfers

This page analyzes inventory movements between stores to improve stock allocation and reduce excess inventory.

### Key Insights

- Total Transfers
- Units Transferred
- Sending Stores
- Receiving Stores
- Units Received by Store
- Units Sent by Store
- Inventory Transfer Details
- Monthly Inventory Transfer Trend
- Transfer Reason Analysis

### Dashboard Preview

![Inventory Transfers](Images/4.%20Inventory%20Transfers.png)

---

## 5. Executive Recommendations

The final page converts analytical findings into business actions that decision-makers can implement immediately.

Rather than only presenting metrics, this dashboard recommends practical actions based on inventory conditions.

### Recommended Actions

- Reorder products below reorder point
- Apply markdowns to dead stock products
- Monitor products at risk before they become dead stock
- Continue balancing inventory between stores
- Prioritize inventory allocation based on demand

### Dashboard Preview

![Executive Recommendations](Images/5.%20Recommendatios.png)

---

# Data Model

The dashboard follows a star schema data model.

### Fact Tables

- Sales Transactions
- Inventory Snapshot
- Inventory Transfers
- Purchase Orders

### Dimension Tables

- Products
- Stores
- Calendar

---

# KPIs

The dashboard includes more than 25 business KPIs, including:

- Total Revenue
- Gross Profit
- Units Sold
- Inventory Value
- Dead Stock Value
- Products Below Reorder Point
- Reorder Quantity
- Products at Stockout Risk
- Inventory Value Below Reorder Point
- Dead Stock Products
- At Risk Products
- Slow Moving Products
- Total Transfers
- Units Transferred
- Sending Stores
- Receiving Stores
- Average Units per Transfer

---

# Tools & Technologies

- Microsoft Excel
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)

---

# Skills Demonstrated

### Data Preparation

- Data Cleaning
- Data Validation
- Business Logic Implementation
- Excel Data Modeling

### Power BI

- Star Schema Design
- Data Modeling
- Relationship Management
- DAX Measures
- Calculated Columns
- Interactive Dashboard Development

### Business Analytics

- Retail Analytics
- Inventory Analytics
- Merchandising Analytics
- KPI Development
- Executive Reporting
- Decision Support

---

# Project Structure

```
Retail-Merchandising-Inventory-Intelligence-Dashboard
│
├── Dashboard
│   └── In Your Shoe Retail Merchandising & Inventory Intelligence Dashboard.pbix
│
├── Data
│   └── Retail Dataset.xlsx
│
├── Images
│   ├── 1. Executive Summary.png
│   ├── 2. Replenishment Analysis.png
│   ├── 3. Markdown & Dead Stock.png
│   ├── 4. Inventory Transfers.png
│   └── 5. Recommendatios.png
│
├── README.md
│
└── LICENSE
```

---

# Future Improvements

Potential enhancements for future versions include:

- Forecasting inventory demand
- Automated replenishment recommendations
- Supplier performance analysis
- Inventory turnover analysis by season
- ABC Inventory Classification
- Sell-through forecasting using machine learning

---

# Author

## Ziad Diab

Marketing & E-commerce Data Analyst

---

## If you found this project interesting, feel free to ⭐ star the repository.
