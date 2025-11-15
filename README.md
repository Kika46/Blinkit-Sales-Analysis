This repository contains an exploratory data analysis (EDA) and a deep dive into the performance of a dataset of Blinkit grocery sales. The analysis aims to understand sales drivers, customer behavior patterns, and outlet performance across attributes such as item type, fat content, outlet size, and location.

📊 Key Performance Indicators (KPIs)
The following core metrics were calculated for the overall dataset:

KPI
Total Sales, 1.20 Million 
Average Sales (per item), 141.0 
Number of Items Sold (Count), 8,523 
Average Item Rating, 3.97 

📈 Analysis Highlights
The analysis revealed several key insights across different dimensions:

1. Total Sales by Item Fat Content

Low-fat items generated the highest total sales: 776,319.68.


Regular items generated total sales of 425,361.80.

Both Low Fat and Regular items had a similar average rating of 3.97.

A pie chart visualization shows that Low-fat items account for 65% of total sales, while Regular items account for 35%.

2. Total Sales by Item Type
The top two item types in terms of total sales are:
Fruits and Vegetables: 178,124.08
Snack Foods: 175,433.92

The bottom five item types by sales are:
Seafood: 9,077.87 
Breakfast: 15,596.70 
Starchy Foods: 21,880.03 
Others: 22,451.89 
Hard Drinks: 29,334.68 

3. Sales by Outlet Size
The largest contributor to total sales is medium-sized outlets with 507,895.73 in sales (42.27% of the total).
Small outlets follow with 444,794.17 in sales (37.01% of the total).
High outlets have the lowest sales contribution at 248,991.58 (20.72% of the total)

4. All Metrics by Outlet Location Type
Outlet Location Type, Total Sales, Avg Sales, No. of Items, Avg Rating
Tier 1, "336,397.81 ",140.87, "2,388 ",3.98 
Tier 2, "393,150.64 ",141.17, "2,785 ",3.96 
Tier 3, "472,133.03 ",140.94, "3,350 ",3.96

📁 Repository Contents
This repository includes the following files:

Blinkit Analysis.ipynb: The main Jupyter Notebook containing the data cleaning, exploratory data analysis (EDA), and visualizations.

Blinkit Dashboard.pbix: The Power BI desktop file containing the interactive dashboard for a comprehensive view of the sales data.

Queries.docx: A document detailing the SQL queries used to extract and calculate the KPIs and key business metrics.







