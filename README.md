# Retail Merchandising & Inventory Intelligence Dashboard — A Power BI Case Study Inspired by In Your Shoe
*A Power BI case study demonstrating how merchandising and inventory analytics can support smarter retail decision-making in the fashion industry.*

## Dataset Disclaimer
This project uses a **simulated dataset** inspired by the business operations of **In Your Shoe**, an Egyptian fashion retailer.

The data was created specifically for portfolio and educational purposes using realistic retail business rules, seasonality patterns, inventory workflows, and merchandising logic. It **does not contain or represent any confidential or proprietary company data**.

The goal of the project is to demonstrate analytical thinking, business understanding, Excel and Power BI development skills in a realistic retail scenario.

---

## Project Overview
This project is an end-to-end **Retail Merchandising & Inventory Intelligence Dashboard** developed as an independent business case study inspired by In Your Shoe, an Egyptian fashion retail brand. The objective was to simulate how a merchandising and inventory analyst would solve real business problems using Excel and Power BI in a modern fashion retail environment.

Using **Microsoft Excel** for data preparation and **Power BI** for data modeling, DAX calculations, and interactive reporting, the dashboard transforms raw retail data into actionable insights that support merchandising, inventory planning, replenishment, markdown decisions, and inventory transfers.

Rather than simply reporting historical metrics, the dashboard converts retail data into business recommendations that help merchandising teams make faster and more informed decisions.

---

## Project Highlights
- Built an end-to-end Business Intelligence solution using Excel and Power BI.
- Designed a Star Schema data model with multiple fact and dimension tables.
- Created 25+ business KPIs using DAX.
- Implemented realistic retail business rules for inventory health classification.
- Developed interactive dashboards focused on executive decision-making.
- Delivered actionable recommendations instead of descriptive reporting.

---

## Business Problem
Retail businesses constantly face inventory-related challenges that directly impact profitability and customer satisfaction.

Some products become overstocked and tie up working capital, while others run out of stock and lead to lost sales. Merchandising teams also need to identify slow-moving products before they become **Dead Stock** and ensure inventory is distributed efficiently across stores.

Without a centralized reporting solution, these decisions become reactive instead of data-driven.

This dashboard helps merchandising teams:
- Reduce excess inventory.
- Prevent stockouts.
- Improve inventory allocation.
- Optimize working capital.
- Support data-driven purchasing decisions.

---

## Business Questions Answered
This dashboard was designed to answer four key business questions:
1. Which products should be reordered?
2. Which products should be discounted?
3. Which products are becoming Dead Stock?
4. Which stores need inventory transfers?

---

## Analytical Approach
The project follows a complete business intelligence workflow commonly used in retail organizations:
1. Defined the business problem and key merchandising questions.
2. Designed a realistic relational dataset based on fashion retail operations.
3. Cleaned, validated, and enhanced the data using business rules in Microsoft Excel.
4. Built a Star Schema data model in Power BI.
5. Created DAX measures and calculated columns to monitor merchandising and inventory performance.
6. Designed interactive dashboards tailored to executive, merchandising, and inventory management needs.
7. Converted analytical findings into actionable business recommendations.

---

## Dataset
The project uses a simulated retail dataset representing one year of merchandising, inventory, and sales operations for a fashion retailer.

The dataset includes:
- 327 Products
- 10 Stores
- Sales Transactions
- Inventory Snapshot
- Purchase Orders
- Inventory Transfers
- Calendar Table

---

## Data Preparation
Before building the dashboard, the dataset was cleaned, validated, and enhanced using business rules to simulate a realistic retail inventory environment.

### Data Cleaning & Validation
- Removed inconsistent inventory records.
- Standardized product and store attributes.
- Validated relationships across all tables.
- Audited sales and inventory calculations.
- Verified revenue calculations.
- Verified Inventory Value calculations.
- Checked data consistency across all business tables.

### Business Logic Implemented
The project includes realistic retail business logic implemented using Excel and DAX. Examples include:
- Product Status Classification
- Product Lifecycle Stage
- Current Inventory Calculation
- Initial Buy Quantity
- Launch Date Derivation
- Sell-Through Rate
- Inventory Value
- Days of Cover
- Reorder Point Logic
- Inventory Health Classification
- Stock Status Logic

---

## Dashboard Pages

### 1. Executive Summary
The Executive Summary provides a high-level overview of business performance and inventory health, allowing decision-makers to quickly understand the current state of the business.

**Key Insights:**
- Total Revenue
- Gross Profit
- Total Units Sold
- Inventory Value
- Dead Stock Value
- Stockout Risk
- Inventory Distribution by Stock Status
- Revenue by Category
- Inventory Investment by Category
- Monthly Revenue Trend
- Top Best-Selling Products
- Top Lowest-Selling Products

![Executive Summary](Images/1.%20Executive%20Summary.png)

### 2. Replenishment Analysis
This page identifies products requiring replenishment before stockouts occur.

**Key Insights:**
- Products Below Reorder Point
- Total Reorder Quantity
- Stockout Risk
- Inventory Value Below Reorder Point
- Reorder Quantity by Category
- Products Requiring Replenishment
- Reorder Quantity by Store
- Current Stock Status

![Replenishment Analysis](Images/2.%20Replenishment%20Analysis.png)

### 3. Markdown & Dead Stock
This page identifies inventory requiring commercial action through markdowns or close monitoring. Inventory Health is dynamically classified using business rules based on Recent Sales Performance, Current Inventory, Sell-Through Rate, and Product Status.

Products are classified as:
- Healthy
- At Risk
- Dead Stock

**Dead Stock** is identified using business rules rather than simply labeling declining products.

**Key Insights:**
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

![Markdown & Dead Stock](Images/3.%20Markdown%20%26%20Dead%20Stock.png)

### 4. Inventory Transfers
This page monitors inventory movement between stores to improve stock allocation and reduce inventory imbalance.

**Key Insights:**
- Total Transfers
- Units Transferred
- Sending Stores
- Receiving Stores
- Units Received by Store
- Units Sent by Store
- Inventory Transfer Details
- Monthly Inventory Transfer Trend
- Transfer Reason Analysis

![Inventory Transfers](Images/4.%20Inventory%20Transfers.png)

### 5. Executive Recommendations
The final page converts analytical findings into actionable business recommendations. Instead of only presenting KPIs, the dashboard highlights operational priorities for merchandising teams.

**Recommendations Include:**
- Products requiring immediate replenishment.
- Products requiring markdowns.
- Inventory requiring close monitoring.
- Store transfer priorities.
- Inventory balancing recommendations.

![Executive Recommendations](Images/5.%20Executive%20Recommendations.png)

---

## Key Business Decisions Supported
The dashboard enables merchandising and inventory teams to:
- Identify products that require immediate replenishment.
- Detect products that should be discounted before becoming Dead Stock.
- Monitor inventory health across the product portfolio.
- Prioritize inventory transfers between stores.
- Improve inventory allocation decisions.
- Reduce working capital tied up in excess inventory.
- Support data-driven merchandising planning.

---

## Data Model
The dashboard follows a Star Schema data model.

### Fact Tables
- Sales Transactions
- Inventory Snapshot
- Purchase Orders
- Inventory Transfers

### Dimension Tables
- Products
- Stores
- Calendar

---

## KPIs
The dashboard includes more than 25 business KPIs, including:
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
- Stockout Risk
- Total Transfers
- Units Transferred
- Sending Stores
- Receiving Stores
- Average Units per Transfer
- Sell-Through Rate
- Days of Cover

---

## Tools & Technologies
- **Microsoft Excel**
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**

---

## Skills Demonstrated

### Data Preparation
- Excel Data Cleaning
- Power Query Data Transformation
- Data Validation
- Data Quality Auditing
- Business Rule Implementation

### Power BI
- Star Schema Modeling
- Fact & Dimension Table Design
- Data Modeling
- Relationship Management
- Interactive Dashboard Design
- KPI Development

### DAX
- Inventory Measures
- Conditional Business Logic
- Calculated Columns
- Measures
- KPI Calculations

### Business Analytics
- Retail Analytics
- Inventory Analytics
- Merchandising Analytics
- Executive Reporting
- Decision Support
- Inventory Optimization

---

## Future Improvements
Potential enhancements include:
- Demand Forecasting using Time Series Models.
- Automated Replenishment Recommendations.
- Supplier Performance Dashboard.
- Inventory Turnover Analysis.
- ABC Inventory Classification.
- Sell-through Forecasting using Machine Learning.

---

## About Me

Hi, I'm **Ziad Diab**.

I'm a Data Analyst specializing in Marketing, E-commerce, and Retail Analytics, passionate about transforming business data into actionable insights using Excel, SQL, and Power BI.

Feel free to connect with me:

**LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/ziad-diab-920b03298/)

*This project was developed independently as a portfolio case study to demonstrate how data analytics can support merchandising and inventory decision-making in the fashion retail industry.*

---

Thank you for taking the time to explore this project.

If you have any feedback or suggestions, I'd be happy to connect and discuss them.

⭐ If you found this project valuable, consider starring the repository.
