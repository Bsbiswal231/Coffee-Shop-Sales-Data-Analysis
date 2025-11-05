# Coffee Shop Sales Dashboard (Sql & PowerBI Project)

### Project Overview:

This project analyzes Coffee Shop Sales Data using Power BI and SQL to uncover key insights into sales performance, customer behavior, and product demand. It explores trends across months, weekdays, and hours, comparing store locations and product categories. The analysis helps identify top-performing products, peak sales periods, and underperforming stores, supporting data-driven decisions to boost overall business performance.

### Datast Used:

<a href="https://github.com/Bsbiswal231/Coffee-Shop-Sales-Data-Analysis/blob/main/Coffee%20Shop%20Sales.xlsx"> Coffee Shop Sales Data </a>

### Questions (KPIs) / Requirement:

##### KPI's Requirements:
 
 1. Total Sales Analysis:- 
   - Calculate the total sales for each respective month.
   - Determine the month-on-month increase or decrease in sales.
   - Calculate the difference in sales between the selected month and the previous month.
  
 2. Total Orders Analysis:-
   - Calculate the total number of orders for each respective month.
   - Determine the month-on-month increase or decrease in the number of orders.
   - Calculate the difference in the number of orders between the selected month and the previous month.
  
 3. Total Quantity Sold Analysis:-
   - Calculate the total quantity sold for each respective month.
   - Determine the month-on-month increase or decrease in the total quantity sold.
   - Calculate the difference in the total quantity sold between the selected month and the previous month.
  
 ##### Charts Requirements:
 
 1. Calendar Heat Map:-
   - Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.
   - Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.
   - Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.
 2. Sales Analysis by Weekdays and Weekends:-
   - Segment sales data into weekdays and weekends to analyze performance variations.
   - Provide insights into whether sales patterns differ significantly between weekdays and weekends.
 3. Sales Analysis by Store Location:-
   - Visualize sales data by different store locations.
   - Include month-over-month (MoM) difference metrics based on the selected month in the slicer.
   - Highlight MoM sales increase or decrease for each store location to identify trends.
 4. Daily Sales Analysis with Average Line:-
   - Display daily sales for the selected month with a line chart.
   - Incorporate an average line on the chart to represent the average daily sales.
   - Highlight bars exceeding or falling below the average sales to identify exceptional sales days.
 5. Sales Analysis by Product Category:-
   - Analyze sales performance across different product categories.
   - Provide insights into which product categories contribute the most to overall sales.
 6. Top 10 Products by Sales:-
   - Identify and display the top 10 products based on sales volume.
   - Allow users to quickly visualize the best-performing products in terms of sales.
 7. Sales Analysis by Days and Hours:-
   - Utilize a heat map to visualize sales patterns by days and hours.
   - Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.

SQL Queries : <a href="https://github.com/Bsbiswal231/Coffee-Shop-Sales-Data-Analysis/blob/main/SQL%20Queries.pdf"> SQL Queries </a>

### Process:

#### 1. Data Collection: 🠺
- Imported the Coffee Shop Sales dataset in Excel format (.xlsx).
- Reviewed columns such as transaction date, transaction time, store location, product category, product type, unit price, and quantity sold to understand data structure and   key relationships.
#### 2. Data Cleaning: 🠺
- Removed duplicate and missing records to maintain data accuracy.
- Corrected inconsistent spellings in product and store names.
- Formatted columns for proper data types (dates, times, numeric values).
- Ensured consistency in categorical data such as product categories and store locations.
#### 3. Data Preparation: 🠺
- Created calculated columns using Power Query and SQL for analysis — including Month, Day, and Hour.
- Aggregated data by time period, product, and location to support trend analysis.
- Structured the dataset for import into Power BI and optimized it for fast processing.
#### 4. Data Analysis: 🠺
- Performed detailed analysis using SQL queries and Power BI measures:
- Total Sales, Total Orders, and Total Quantity Sold
- Month-over-Month (MoM) growth calculations
- Sales by store location, product category, and product type
- Weekday vs. Weekend performance
- Hourly sales pattern analysis
#### 5. Dashboard Development: 🠺
- Designed an interactive Power BI dashboard with a clean, business-style layout.
- Added KPIs for Total Sales, Orders, and Quantity Sold.
- Used visuals like Calendar Heatmap, Bar/Line Charts, and Donut Charts.
- Enabled slicers for Month, Store Location, and Product Category to make the dashboard dynamic and user-friendly.
#### 6. Insights Generation: 🠺
- Identified peak sales hours (8 AM – 12 PM) indicating the morning coffee rush.
- Found that weekend sales outperform weekdays due to higher customer traffic.
- Highlighted top-performing stores and products driving maximum revenue.
- Recognized underperforming categories for targeted improvement.

### Dashboard:
<img width="1449" height="756" alt="Dashboard" src="https://github.com/user-attachments/assets/809dc870-4811-408b-ac80-5655054017a9" />

### Final Conclusion: 
- The Coffee Shop Sales Analysis effectively converted raw sales data into clear business insights using SQL and Power BI. It identified top-performing stores, best-selling products, and peak sales hours, showing that weekends and mornings drive the most revenue. The dashboard enables data-driven decisions to improve sales performance and profitability.
