# Data Portfolio
## Project Title: Sales Analysis

### Overview
This project analyzes sales data from various stores across different regions and markets. The dataset includes key metrics such as revenue, units sold, fiscal period, and line of business, providing valuable insights into sales performance across multiple dimensions. The goal of the analysis is to uncover trends, identify areas of improvement, and provide actionable insights to enhance business operations.

### Project Objectives
The main objectives of this project are:  
- To understand the sales performance by analysing the revenue and units sold across various regions, markets, and stores.
- To Identify Top-Performing Stores and Markets by analysing which stores are the highest revenue generators.
- To To determine which business lines and sales models contribute most to overall revenue by analyzing the Line of Business and Sales Models.
- To Provide Data-Driven Recommendations based on the analysis.

### Data Source
The primary source of the data used for this project is ....

### Dataset Description
The Dataset consist of the following columns; 
- Region: Geographical area where the store operates.
- Market: Subdivision within the region to identify specific target markets.
- Store: Unique ilocation of each store
- Trade Date: Date when the transaction occurred.
- Fiscal Period: The accounting period in which the transaction was recorded.
- Line of Business: The unique organization sector that the or transaction falls under.
- Revenue: Total amount generated from sales.
- Units Sold: The number of units sold in each transaction.
- Transaction Category: Classification of the transaction based on the unit sold (Low, medium, high).

### Tools and Methods used
This analysis was done using microsoft excel.

#### Data Cleaning
Used Excel functions such as IF, TRIM, and DATEVALUE to clean the data.

#### Data Analysis
Used pivot tables to;
Compare sales (revenue and units sold) across different regions and markets
Rank stores by total revenue and units sold
Identifying trends and patterns in the fiscal periods

#### Data Visualization
Created Excel charts (bar charts, line charts, and pie charts) to visualize key metrics, such as revenue trends, top-performing stores, and market performance.
Used conditional formatting to highlight important trends and insights in the data (e.g., top 10 stores, low-performing markets).

### Formulas used
``` excel
=IFS(J3<=20,"Low",J3<=50,"Medium",J3>=50,"High")
```
## Analysis
### Revenue by Region




