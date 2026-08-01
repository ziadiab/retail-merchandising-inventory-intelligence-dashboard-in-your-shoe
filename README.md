# Retail Merchandising & Inventory Intelligence Dashboard for In Your Shoe

## Project Overview

This project is an end-to-end **Retail Merchandising & Inventory Intelligence Dashboard** developed for **In Your Shoe**, a fashion retail brand.

Using **Microsoft Excel** for data preparation and **Power BI** for data modeling, DAX calculations, and interactive reporting, the dashboard transforms raw retail data into actionable insights that support merchandising, inventory planning, replenishment, markdown decisions, and inventory transfers.

Rather than simply reporting historical metrics, the dashboard converts retail data into business recommendations that help merchandising teams make faster and more informed decisions.

---

# Project Highlights

- Built an end-to-end Business Intelligence solution using Excel and Power BI.
- Designed a Star Schema data model with multiple fact and dimension tables.
- Created 25+ business KPIs using DAX.
- Implemented realistic retail business rules for inventory health classification.
- Developed interactive dashboards focused on executive decision-making.
- Delivered actionable recommendations instead of descriptive reporting.

---

# Business Problem

Retail businesses constantly face inventory-related challenges that directly impact profitability and customer satisfaction.

Some products become overstocked and tie up working capital, while others run out of stock and lead to lost sales. Merchandising teams also need to identify slow-moving products before they become dead stock and ensure inventory is distributed efficiently across stores.

Without a centralized reporting solution, these decisions become reactive instead of data-driven.

This dashboard helps merchandising teams:

- Reduce excess inventory
- Prevent stockouts
- Improve inventory allocation
- Optimize working capital
- Support data-driven purchasing decisions

---

# Business Questions Answered

This dashboard was designed to answer four key business questions:

- Which products should be reordered?
- Which products should be discounted?
- Which products are becoming dead stock?
- Which stores need inventory transfers?

---

# Dataset

The project uses a simulated retail dataset representing one year of operations for a fashion retailer.

The dataset includes:

- 327 Products
- 10 Stores
- Sales Transactions
- Inventory Snapshot
- Purchase Orders
- Inventory Transfers
- Calendar Table

---

# Data Preparation

Before building the dashboard, the dataset was cleaned, validated, and enhanced using business rules to simulate a realistic retail inventory environment.

## Data Cleaning & Validation

- Removed inconsistent inventory records
- Standardized product and store attributes
- Validated relationships across all tables
- Audited sales and inventory calculations
- Verified revenue calculations
- Verified inventory value calculations
- Checked data consistency across all business tables

## Business Logic Implemented

The project includes realistic retail business logic implemented using Excel and DAX.

Examples include:

- Product Status Classification
- Product Lifecycle Stage
- Current Inventory Calculation
- Initial Buy Quantity
- Launch Date Derivation
- Sell Through Percentage
- Inventory Value
- Days of Cover
- Reorder Point Logic
- Inventory Health Classification
- Stock Status Logic

---

# Dashboard Pages

## 1. Executive Summary

The Executive Summary provides a high-level overview of business performance and inventory health, allowing decision-makers to quickly understand the current state of the business.

### Key Insights

- Total Revenue
- Gross Profit
- Total Units Sold
- Inventory Value
- Dead Stock Value
- Products at Stockout Risk
- Inventory Distribution by Stock Status
- Revenue by Category
- Inventory Investment by Category
- Monthly Revenue Trend
- Top Best-Selling Products
- Top Lowest-Selling Products

### Dashboard Preview

![Executive Summary](Images/1.%20Executive%20Summary.png)

---

## 2. Replenishment Analysis

This page identifies products requiring replenishment before stockouts occur.

### Key Insights

- Products Below Reorder Point
- Total Reorder Quantity
- Products at Stockout Risk
- Inventory Value Below Reorder Point
- Reorder Quantity by Category
- Products Requiring Replenishment
- Reorder Quantity by Store
- Current Stock Status

### Dashboard Preview

![Replenishment Analysis](Images/2.%20Replenishment%20Analysis.png)

---

## 3. Markdown & Dead Stock

This page identifies inventory requiring commercial action through markdowns or close monitoring.

Inventory Health is dynamically classified using business rules based on:

- Recent Sales Performance
- Current Inventory
- Sell-Through Percentage
- Product Status

Products are classified as:

- Healthy
- At Risk
- Dead Stock

Dead Stock is identified using business rules rather than simply labeling declining products.

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

This page monitors inventory movement between stores to improve stock allocation and reduce inventory imbalance.

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

The final page converts analytical findings into actionable business recommendations.

Instead of only presenting KPIs, the dashboard highlights operational priorities for merchandising teams.

### Recommendations Include

- Products requiring immediate replenishment
- Products requiring markdowns
- Inventory requiring close monitoring
- Store transfer priorities
- Inventory balancing recommendations

### Dashboard Preview

![Executive Recommendations](Images/5.%20Recommendatios.png)

---

# Data Model

The dashboard follows a **Star Schema** data model.

## Fact Tables

- Sales Transactions
- Inventory Snapshot
- Purchase Orders
- Inventory Transfers

## Dimension Tables

- Products
- Stores
- Calendar

---

# KPIs

The dashboard includes more than **25 business KPIs**, including:

- Total Revenue
- Gross Profit
- Total Units Sold
- Inventory Value
- Dead Stock Value
- Dead Stock Products
- At-Risk Products
- At-Risk Inventory Value
- Products Below Reorder Point
- Inventory Value Below Reorder Point
- Reorder Quantity
- Products at Stockout Risk
- Total Transfers
- Units Transferred
- Sending Stores
- Receiving Stores
- Average Units per Transfer
- Sell Through Percentage
- Days of Cover

---

# Tools & Technologies

- Microsoft Excel
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)

---

# Skills Demonstrated

## Data Preparation

- Excel Data Cleaning
- Power Query Data Transformation
- Data Validation
- Data Quality Auditing
- Business Rule Implementation

## Power BI

- Star Schema Modeling
- Fact & Dimension Table Design
- Data Modeling
- Relationship Management
- Interactive Dashboard Design
- KPI Development

## DAX

- Inventory Measures
- Conditional Business Logic
- Calculated Columns
- Measures
- KPI Calculations

## Business Analytics

- Retail Analytics
- Inventory Analytics
- Merchandising Analytics
- Executive Reporting
- Decision Support
- Inventory Optimization

---

# Project Structure

```
Retail-Merchandising-Inventory-Intelligence-Dashboard
│
├── Dashboard
│   └── In Your Shoe Retail Merchandising & Inventory Intelligence Dashboard.pbix
│
├── Data
│   └── In_Your_Shoe_Dataset.xlsx
│
├── Images
│   ├── 1. Executive Summary.png
│   ├── 2. Replenishment Analysis.png
│   ├── 3. Markdown & Dead Stock.png
│   ├── 4. Inventory Transfers.png
│   └── 5. Executive Recommendations.png
│
└── README.md
```

---

# Future Improvements

Potential enhancements include:

- Demand Forecasting using Time Series Models
- Automated Replenishment Recommendations
- Supplier Performance Dashboard
- Inventory Turnover Analysis
- ABC Inventory Classification
- Sell-through Forecasting using Machine Learning

---

# Author

## Ziad Diab

Marketing & E-commerce Data Analyst

---

⭐ If you found this project interesting, consider starring the repository.
