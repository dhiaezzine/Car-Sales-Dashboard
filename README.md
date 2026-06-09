# Car-Sales-Dashboard
dynamic Car Sales Analytics Dashboard built in Power BI
🚗 Car Sales Analytics Dashboard | Power BI
🔥 Transforming Raw Sales Data into Actionable Business Insights

This project is a professional Power BI end-to-end dashboard designed for a car dealership business to monitor sales performance, track KPIs in real time, and support strategic decision-making.

It simulates a real-world business intelligence solution used by sales and executive teams to understand what is selling, where, and why.

🎯 Business Problem

Car dealership companies generate large volumes of sales data daily, but without proper analytics, it becomes difficult to:

Track overall sales performance
Identify top-performing car models and regions
Monitor revenue trends over time
Compare current performance with previous years
Make fast, data-driven business decisions

👉 This dashboard solves these challenges by providing a single source of truth for sales analytics.

🚀 Project Objectives
Build an interactive and dynamic Power BI dashboard
Track key sales KPIs (Sales, Cars Sold, Average Price)
Analyze performance over time (MTD, YTD, YOY)
Identify trends across products, regions, and companies
Enable drill-down analysis for deeper insights
📊 Key Business KPIs
💰 Sales Performance
Year-to-Date (YTD) Total Sales
Month-to-Date (MTD) Total Sales
Year-over-Year (YOY) Growth
Difference vs Previous Year (PTYD)
📈 Pricing Insights
YTD Average Price
MTD Average Price
YOY Growth in Average Price
🚘 Sales Volume
YTD Cars Sold
MTD Cars Sold
YOY Growth in Cars Sold
📊 Dashboard Features & Visuals
📉 Sales Trend Analysis
Weekly YTD Sales Trend (Line Chart)
Identify seasonal patterns and fluctuations
🚘 Product Performance
Sales by Body Style (Pie Chart)
Sales by Car Color (Pie Chart)
🌍 Geographic Insights
Cars Sold by Dealer Region (Map Visualization)
🏢 Company Performance
Company-wise Sales Performance Table
📋 Detailed Transaction View
Complete dataset view including:
Car Model
Body Style
Color
Sales Amount
Dealer Region
Date of Sale
🧠 Key DAX Measures
YTD Total Sales =
TOTALYTD(SUM(CarSales[Sales]), 'Date'[Date])
MTD Total Sales =
TOTALMTD(SUM(CarSales[Sales]), 'Date'[Date])
YOY Growth Sales =
DIVIDE([YTD Total Sales] - [PYTD Total Sales], [PYTD Total Sales])
🛠️ Tech Stack
📊 Power BI Desktop
🔄 Power Query (ETL & Data Cleaning)
🧮 DAX (Advanced Calculations)
📁 Excel / CSV Dataset
🧱 Data Modeling (Star Schema)
📸 Dashboard Preview

<img width="1436" height="805" alt="dashboard_overview" src="https://github.com/user-attachments/assets/33593fc3-3eb9-485b-b93f-6ba20709b348" />


Executive Overview Page
Sales Analysis Page
Product & Region Breakdown

📌 Tip: A good screenshot can increase recruiter attention significantly.

💡 Key Insights Delivered

This dashboard enables decision-makers to:

Identify best-selling car models
Track high-performing regions
Understand pricing impact on sales
Detect weekly and seasonal trends
Compare performance vs last year in seconds
📌 Business Impact

✔ Faster decision-making through real-time insights
✔ Improved visibility of sales performance
✔ Better regional and product strategy planning
✔ Enhanced reporting efficiency for management

🔮 Future Enhancements
🔮 Predictive Sales Forecasting (AI integration)
⚡ Real-time API data integration
👥 Customer segmentation analysis
🧭 Advanced drill-through dashboards
📊 Automated reporting system
