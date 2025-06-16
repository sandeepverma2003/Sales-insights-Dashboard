📊 Sales Insights Dashboard — Top 5 Products & Customers
🔍 Overview
This project focuses on analyzing a sample sales dataset to identify the Top 5 Products and Top 5 Customers contributing to overall revenue. The goal is to simulate a real-world business intelligence scenario where quick and impactful insights are extracted from raw data using SQL and visualized using Power BI.

🛠️ Tools & Technologies
SQL (Data Analysis & Querying)
Power BI (Dashboard Creation & Visualization)
Microsoft Excel (For initial dataset management)

📈 Project Objectives
Identify Top 5 Best-Selling Products by total sales amount.
Determine Top 5 Customers based on total purchase value.
Visualize insights through a Power BI dashboard with clear, business-friendly visuals.

🧩 Dataset Summary
The dataset contains records of product sales including:
Product Name / Category
Customer Name
Sales Value
Order Date / Region 

🔎 Key SQL Operations
Aggregated total sales using SUM() grouped by Product and Customer.
Sorted data using ORDER BY to rank highest contributors.
Filtered Top 5 records using LIMIT or TOP clause (based on SQL dialect).

SELECT ProductName, SUM(SalesAmount) AS TotalSales
FROM SalesData
GROUP BY ProductName
ORDER BY TotalSales DESC
LIMIT 5;

📊 Power BI Dashboard Features
Bar Charts showing:
Top 5 Products by Sales
Top 5 Customers by Revenue
Summary Cards displaying:
Total Sales
Total Transactions
Interactive Filters by Category or Region
Clean, minimal design for easy data interpretation

