# Sales Analytics Dashboard

## Project Overview

This beginner-friendly data analytics project explores sales data using
**Microsoft Excel** and **Microsoft Power BI**. The goal is to summarize
sales performance, compare regions and product categories, track order
statuses, and view monthly sales trends through an interactive
dashboard.

## Tools Used

-   Microsoft Excel
-   Microsoft Power BI
-   DAX (Data Analysis Expressions)
-   GitHub

## Dashboard Features

### Key Performance Indicators (KPIs)

-   **Total Net Sales:** Sum of the Net Sales column
-   **Total Orders:** Distinct count of Order IDs
-   **Average Order Value:** Average of Net Sales
-   **Delivered Orders:** Distinct count of Order IDs where Order Status
    is `Delivered`

### Visualizations

1.  Net Sales by Region --- Clustered Column Chart
2.  Orders by Status --- Doughnut Chart
3.  Net Sales by Product Category --- Bar Chart
4.  Monthly Net Sales Trend --- Line Chart
5.  Net Sales by Sales Representative --- Bar Chart

### Interactive Filters

-   Region
-   Order Status
-   Product Category
-   Order Date

## Key Results

The current dataset contains 100 orders.

  Metric                     Result
  --------------------- -----------
  Total Net Sales          ₹564,692
  Total Orders                  100
  Average Order Value     ₹5,646.92
  Delivered Orders               65

*Note: Total Net Sales currently includes all order statuses, including
returned and cancelled orders.*

## Files in This Repository

-   `Sales_Analytics_Project.xlsx` --- Excel workbook containing the
    project data and calculations.
-   `Sales_Analytics_Dashboard.pbix` --- Power BI dashboard file.
-   `Dashboard_Screenshot.png` --- Screenshot of the completed
    dashboard.
-   `README.md` --- Project documentation.

*Change the example file names above if your actual uploaded files have
different names.*

## How to View the Dashboard

1.  Download the `.pbix` file from this repository.
2.  Open it using Microsoft Power BI Desktop.
3.  Use the slicers to filter the dashboard by region, order status,
    category, or order date.

## Learning Outcomes

Through this project, I practised:

-   Working with sales data in Excel
-   Using Excel formulas and lookup functions
-   Creating Pivot Tables
-   Building KPI measures using DAX
-   Creating charts and interactive slicers in Power BI
-   Presenting data through a dashboard

## Author

Created as part of my Data Analytics learning journey.
