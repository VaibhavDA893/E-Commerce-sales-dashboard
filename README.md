

 📊 E-Commerce Sales Dashboard

[E-Commerce Sales Dashboard](./Screenshot%202025-05-02%20165839.png)

 📝 Project Overview

This project is a comprehensive E-Commerce Sales Dashboard** built using Power BI, designed to help businesses monitor, analyze, and gain insights into their sales performance. It leverages SQL for data extraction, Excel for pre-processing and data cleansing, and DAX in Power BI to create powerful metrics and KPIs.

The dashboard provides a holistic view of sales trends, customer behavior, product performance, and region-wise growth, enabling data-driven decision-making.



 Tools & Technologies Used

Microsoft Power BI – for interactive data visualization and dashboard creation.
DAX (Data Analysis Expressions) – to write calculated columns, measures, KPIs, and time intelligence functions.
Microsoft Excel – used for initial data cleaning, transformation, and manual adjustments.
SQL – for data extraction and structuring from a relational database.



  Key Features of the Dashboard

1. Total Sales Overview
   Displays overall revenue generated with dynamic time period filtering (monthly, quarterly, yearly).

2. Profit & Cost Analysis
   Breakdown of total profit, cost of goods sold (COGS), and profit margins.

3. Sales Trend Analysis
   Line and bar charts showing monthly/yearly trends in sales and profits.

4. Top Performing Products
   Highlights best-selling products by revenue and quantity sold.

5. Customer Demographics & Behavior
   Segment customers based on purchase history and analyze their contribution to revenue.

6. Region-wise Sales Distribution
   Map visuals and bar charts show which geographic regions contribute most to the sales.

7. Dynamic Filters & Slicers
   Users can filter data based on:

    Date Range
    Product Category
    Country/Region
    Sales Channel (Online/Offline)



 📂 Project Structure

📁 E-Commerce-Sales-Dashboard
│
├── 📊 PowerBI_Dashboard.pbix        Power BI project file
├── 📈 Excel_Data.xlsx               Raw and cleaned dataset
├── 📄 SQL_Query.sql                 SQL queries for data extraction
├── 📸 Screenshot_2025-05-02.png     Dashboard screenshot
└── 📄 README.md                     Project documentation




 🔎 DAX Highlights

Some of the advanced DAX measures used in this project include:

DAX
Total Sales = SUM(Sales[Revenue])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

Sales LY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date]))

YOY Growth = DIVIDE([Total Sales] - [Sales LY], [Sales LY])


These measures help track growth and performance over time and support powerful visual storytelling.



 📈 Insights Generated

 Identified top 10 high-performing products that contribute to 40% of sales.
 Discovered a 20% increase in online sales over the past 6 months.
 Found that Region X underperforms compared to others, suggesting a need for targeted marketing.
 Sales are seasonal, with a peak during Q4 every year.


 How to Use This Dashboard

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/E-Commerce-Sales-Dashboard.git
   ```
2. Open the Power BI file: `PowerBI_Dashboard.pbix`
3. Refresh the data (ensure Excel file and data sources are in the same directory).
4. Interact with filters/slicers to explore insights dynamically.


📅 Future Enhancements

* Add forecasting models using Power BI's **AI Insights**.
* Integrate with **real-time sales API** for live updates.
* Add **customer segmentation** using clustering (K-means).

