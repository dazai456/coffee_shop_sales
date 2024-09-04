# Coffee Shop Sales Analysis

This repository contains a detailed analysis of coffee shop sales data. The project was conducted using Excel's Power Query, Power Pivot, and Power BI to clean, process, analyze, and visualize the data, resulting in insightful reports and dashboards.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Preparation](#data-preparation)
  - [Data Import and Cleaning](#data-import-and-cleaning)
  - [Data Normalization](#data-normalization)
  - [Data Types Validation](#data-types-validation)
- [Data Analysis](#data-analysis)
  - [Date Table Creation](#date-table-creation)
  - [Measure Creation](#measure-creation)
- [Reporting](#reporting)
  - [Dynamic Sales Report](#dynamic-sales-report)
  - [Transaction Report](#transaction-report)
  - [Slicers](#slicers)
- [Dashboard Creation](#dashboard-creation)
  - [Power BI Dashboard](#power-bi-dashboard)
- [Contributing](#contributing)
- [DataSource]

## Project Overview

The aim of this project is to analyze sales data from a coffee shop chain to derive key insights about sales performance across various locations and product categories. The project utilized Excel's Power Query and Power Pivot for data preparation and analysis, and Power BI for advanced data visualization.

## Data Preparation

### Data Import and Cleaning

- Imported the sales data into Power Query.
- Checked the data for:
  - **Duplicates**: Removed any duplicate entries to ensure data integrity.
  - **Null Values**: Handled missing values appropriately to maintain the consistency of the dataset.
  - **Normalization**: Ensured that data was standardized across all records.
  - **Data Types**: Validated that all data types were correct for analysis (e.g., dates, numbers, text).

### Data Normalization

- Normalized the dataset to ensure consistency, making it easier to perform accurate analyses and comparisons.

### Data Types Validation

- Verified that all columns were assigned the correct data types, such as dates for date columns and numeric types for financial data.

## Data Analysis

### Date Table Creation

- Created a Date Table in Power Pivot to facilitate time-based analysis, enabling the calculation of metrics like monthly and quarterly revenue.

### Measure Creation

Developed key performance measures, including:

- **Revenue**: Total sales revenue.
- **Revenue Last Month**: Sales revenue for the previous month.
- **Revenue vs. Revenue Last Month**: Comparison of current month revenue with the previous month.
- **Revenue Last Quarter**: Sales revenue for the previous quarter.
- **Revenue vs. Revenue Last Quarter**: Comparison of current quarter revenue with the previous quarter.
- **Average Revenue**: Average revenue over a specified period.

## Reporting

### Dynamic Sales Report

- Created a dynamic sales report in Excel, which updates automatically based on the selected slicers.

### Transaction Report

- Developed a transaction report to analyze individual sales transactions, helping to track performance at a granular level.

### Slicers

Added slicers for:

- **Month**: Filter data by specific months.
- **Quarter**: Filter data by specific quarters.
- **Store Location**: Filter data by different store locations.
- **Product Category**: Filter data by different product categories.

## Dashboard Creation

### Power BI Dashboard

- Imported the data model into Power BI to create interactive dashboards.
  - **Sales Dashboard**: A comprehensive overview of sales performance.
  - **Transactions Dashboard**: Detailed insights into individual transactions.

## Contributing

Contributions are welcome! Please feel free to fork the repository, make improvements, and submit a pull request.

## Data Source 
https://www.kaggle.com/datasets/ahmedmohamedibrahim1/coffee-shop-sales-dataset