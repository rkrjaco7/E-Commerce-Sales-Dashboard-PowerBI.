# E-Commerce-Sales-Dashboard-PowerBI.

#Project Overview

This project involves the creation of an interactive Sales Dashboard for Madhav Store, an online retail business. The goal was to provide the store owner with a visual tool to track sales, identify top-performing regions, and analyze profit margins to drive data-backed business decisions.


#Key Features & Insights

Sales Tracking: Visualized total sales and profit trends over time (Monthly/Quarterly).

Customer Insights: Identified top 5 high-value customers based on total spending.

Geographic Analysis: Analyzed sales performance across different Indian states to identify expansion opportunities.

Category Breakdown: Monitored the most popular product categories (Clothing, Electronics, Furniture) and their contribution to total revenue.

Dynamic Filtering: Implemented Slicers for Quarter and State-level granularity.

#Technical Skills Demonstrated

1. Data Cleaning & Transformation (Power Query)
   
Performed ETL (Extract, Transform, Load) operations to clean the raw "Madhav Store" CSV data.

Handled data type conversions (e.g., converting text strings to Date formats).

Used Group By and Conditional Columns for data categorization.

2. Data Modeling
   
Established a One-to-Many relationship between the Orders and Details tables using a unique Order ID.

Optimized the schema for efficient filtering across the dashboard.

3. DAX (Data Analysis Expressions)

   Created calculated columns and measures to derive business KPIs.
   Formula Example (Average Order Value):$$AOV = \frac{\text{Total Amount}}{\text{Total Quantity}}$$

4. Data Visualization
   
Bar & Column Charts: For profit and sales comparison.

Donut Charts: For category-wise sales distribution.

Cards: For high-level KPI visibility (Total Profit, Total Quantity, AOV).

#How to Use

Download the .pbix file from this repository.

Open the file using Power BI Desktop.

Interact with the Quarter and State slicers on the top right to filter the visuals
