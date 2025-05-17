📊 Store Sales Dashboard using Power BI

⭐ Objective
Build an interactive Power BI dashboard to track sales KPIs and trends.
Help stakeholders make data-driven decisions using clear and real-time insights.

⭐ Synopsis
The dashboard is based on fictional store sales data.
It offers YoY comparisons, segment-wise performance, shipping trends, and geographical analysis.
Used Power BI features like DAX, slicers, maps, and charts for a dynamic user experience.

⭐ Data Analysis Performed
🔢 Key KPIs Tracked:
Total Sales – 1.57M
Total Profit – 175.26K
Quantity Sold – 22K units
Average Delivery Days – 4

📈 Breakdown of Insights:
Customer Segments – Consumer (48%), Corporate (33%), Home Office (19%)
Monthly Profit Trends – Identifies seasonal spikes, especially in Q4 2020
Shipping Preferences – Standard Class dominates; room for faster modes
Payment Preferences – COD (43%) leads, followed by Online (35%) and Cards (22%)
Top Categories – Office Supplies leads; Phones and Chairs are top sub-categories
Regional Sales – U.S. map shows which states are driving performance

⭐ Dashboard Usefulness
Business Owners – Spot top products/regions; optimize revenue
Marketing Teams – Plan promotions based on customer segments
Operations – Analyze delivery efficiency and shipping preferences
Finance Teams – Assess profit trends and payment behaviors

⭐ Upstream Data Flow
Data Sources – Sales transactions, customer data, shipping details
Preparation – Cleaned and transformed using Power Query
Modeling – Relationships built across orders, customers, products, shipping

⭐ Downstream Outputs
Interactive Dashboard – For daily operational and strategic decisions
Automated Reports – Via scheduled refresh and alerting in Power BI Service
Stakeholder Insights – Real-time filtering and exploration features

⭐ Visuals and Their Use
KPI Cards – Quick glance at key metrics
Donut Charts – Customer Segment and Payment Mode distribution
Line Charts – Monthly YoY performance trends
Bar Charts – Top Categories, Sub-Categories, and Ship Modes
Geo Map – Regional sales/profit analysis
Slicers – Filters by Region, Category, Ship Mode
⭐ Common DAX Used
TOTALMTD() – Returns Month-To-Date values.
TOTALYTD() – Returns Year-To-Date values.
CALCULATE() – Performs context-based calculations.
RANKX() – Ranks products/customers by sales.
ALL() – Removes filters for ranking or total context.
IF(), SWITCH() – Used for custom logic.
DIVIDE() – Safe division to avoid errors.

⭐ Conclusion:
This project demonstrates how Power BI turns raw data into strategic insights.
The dashboard is an effective tool for monitoring, analyzing, and improving sales performance.





