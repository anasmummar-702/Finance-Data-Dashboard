# Executive finance summary report-Dashboard
## Project Summary
This project involves the creation and analysis of an executive-level finance dashboard designed to monitor key financial performance indicators (KPIs) over time, by product, and by geography. The dashboard focuses on two primary metrics: Sum of Profit and Sum of Sales. The analysis period spans across 2013 and 2014, with drill-down capability by Year, Quarter, Month, and Day. The primary objective is to identify profitable trends, best-selling segments/products, and key regional contributors.

## Data Used
-<a href="https://github.com/anasmummar-702/Finance-Data-Dashboard/blob/main/Financial%20Sample%20(1).xlsx">Data</a>

## Key Performance Indicators (KPIs) and Business Questions

1.What is the precise profit margin for the month that recorded the peak Sum of Profit (appears to be late 2014)?

2.How much does the top-performing segment (likely ENTERPRISE) contribute as a percentage of the total sales shown in the Sum of Sales by Product and Segment chart?

3.Which specific Country within the highest-profit region (e.g., North America or Europe) is the single largest profit contributor?

4.What is the Net Profit trend when compared to the Sum of Sales trend for the periods shown in 2013 and 2014?

5.Why is the sales volume for Paseo dominated by the ENTERPRISE segment, and is there potential to grow its sales in other segments?

6.Are the fluctuations in the Sum of Profit line chart correlated with seasonal sales patterns or specific marketing campaigns?

7.What is the contribution of the CHANNEL PARTNERS segment, which appears to be lower across all products, and how can its sales be boosted?

8.Which product has the highest average price point, and how does that influence its overall sales volume? (Requires external data)

9.For the product with the lowest sales (e.g., Carretera), is its low volume offset by a significantly higher profit margin?

10.Are there any segments that are profitable in one region (e.g., North America) but unprofitable in another (e.g., Europe)?

-DashBoard Interaction <a href="https://github.com/anasmummar-702/Finance-Data-Dashboard/blob/main/Screenshot%202025-10-21%20175737.png">View Dashboard</a>

## Project Process and Steps

-Data Acquisition: Connected the BI tool (Power BI) to the source financial data (General Ledger, Sales Transactions, etc.).

-Data Transformation (ETL): Used Power Query Editor to clean and shape the data, ensuring correct data types for sales, profit, dates, and geographic identifiers.

-Data Modeling: Established a calendar table and linked all financial tables to enable time-based drill-down capabilities.

-Measure Creation: Developed custom DAX calculations for the primary KPIs: Sum of Profit, Sum of Sales, and potentially calculated measures for profit margins (not explicitly shown but necessary for analysis).

-Visualization: Designed the dashboard with a professional, executive-friendly layout. Utilized a time-series line chart for trends, a map for geographic analysis, and a clustered bar chart for sales segmentation.

-Review and Deployment: Verified the financial accuracy of all metrics and published the report for executive team consumption.

## Dashboard

<img width="1012" height="559" alt="Screenshot 2025-10-21 175737" src="https://github.com/user-attachments/assets/9524301f-5f0a-4ec6-8640-321f82fc7248" />

## Model View
creating a realationship with an another tables and add measures, Relational Data Model consisting of two tables, which is characteristic of a Star Schema used in data warehousing and business intelligence tools like Power BI.

example:

<img width="995" height="633" alt="Screenshot 2025-10-21 180220" src="https://github.com/user-attachments/assets/896a00e4-dbf2-49c2-aa53-4db60f64304c" />

## 📊 Project Insights
*Volatile Profitability: The Sum of Profit line chart shows significant month-to-month volatility, with a clear drop in profit occurring in mid-2014, followed by a strong recovery. This volatility requires investigation into cost structures or exceptional sales events.

*Segment Concentration: The ENTERPRISE and GOVERNMENT segments are the dominant revenue drivers, particularly for the Paseo product. The company's revenue stream is heavily reliant on these large accounts.

*Product Disparity: Paseo and VTT are the clear sales leaders, while products like Velo and Carretera require a closer look to determine if low sales volume is due to product lifecycle, market fit, or lack of focus.

*Global Reach: Profit is generated from multiple global regions (North America, Europe, Latin America), suggesting a diversified global business model.


## 🧠 Final Conclusion
The Executive Finance Summary Report successfully provides the necessary visibility for executive management. The analysis confirms a strong sales base driven by key enterprise/government segments and specific products. The most critical area for executive focus is the volatility and periods of decline in the profit trend, which necessitates a deeper dive into cost of goods sold (COGS) and operational efficiency during those specific months. Future strategic efforts should explore how to boost sales in the Midmarket and Small Business segments to create a more diversified and resilient revenue base.
