# Full-Analysis-By-Python
Project Overview

This project analyzes sales data from an Excel file (Sales.xlsx) using Python, Pandas, and Matplotlib. The primary goal is to extract insights from sales records by creating a Star Schema data model and visualizing key metrics, such as total sales by year, month, order status, and territory. The analysis includes data preprocessing, dimension table creation, and the generation of visualizations like line plots and potential cards for key metrics.

Features





Data Preprocessing: Loads and cleans sales data from an Excel file using Pandas.



Star Schema Implementation: Creates dimension tables (Dim_OrderDate, Dim_DueDate, Dim_ShipDate, Dim_Status, Dim_Territory) from a single fact table for efficient data analysis.



Visualizations:





Line plot showing monthly sales trends for the years 2011–2014 with data labels.



Customizable styling with a dark theme for better visual appeal.



Key Metrics: Calculates and visualizes total sales and sales distribution by order status, with potential for dashboard-like "card" displays for metrics like total sales.

Technologies Used





Python: Core programming language.



Pandas: For data manipulation and Star Schema creation.



Matplotlib: For creating visualizations like line plots.



Jupyter Notebook: For interactive development and analysis.

Dataset

The dataset (Sales.xlsx) contains sales records with columns such as:





OrderDate, DueDate, ShipDate: Date-related fields.



Status, StatusID: Order status (e.g., Shipped, Cancelled).



Territory, TerritoryGroup: Geographic sales regions.



LineTotal: Sales amount per order line.



Other fields like Product, CustomerID, OrderQty, etc.

Project Structure





Data Loading: Imports the Excel file into a Pandas DataFrame.



Star Schema:





Dimension tables created for dates (OrderDate, DueDate, ShipDate), status, and territory.



Date fields transformed into unique IDs (e.g., YYYYMMDD format).



Visualizations:





A line plot comparing monthly sales across 2011–2014 with data labels for clarity.



Dark-themed styling with customizable colors and fonts.



Analysis: Aggregates sales by status and territory for insights.
