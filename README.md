# Superstore-Sales-Performance-Dashboard

This project analyzes sales performance using the Sample Superstore dataset and presents insights through an interactive Power BI dashboard. The dashboard focuses on sales trends, profitability, regional performance, and top-performing products to support business decision-making.

🛠️ Tools Used
- Microsoft Power BI Desktop
- Power Query (Data Cleaning & Transformation)
- DAX (Calculated Measures)

📂 Dataset
- Dataset: Sample Superstore
- Data Type: Sales & Orders
Key Fields:
- Order Date, Ship Date
- Category, Sub-Category
- Region, City
- Sales, Profit, Quantity, Discount

📊 Visualizations Included
- Sales Trend by Year – Line chart (2014–2017)
- Sales by Category – Column chart
- Top 10 Products by Sales – Bar chart (Top N filter)
- Sales by Region – Column chart

🔍 Key Insights
- Sales grew strongly from 2014 to 2016, showing business expansion
- Technology is the highest revenue-generating category
- A small group of products contributes a large share of revenue
- West and East regions perform best; South underperforms
- Overall profit margin is ~13.56%, with scope to optimize discounts

⚙️ Challenges & Solutions
- Date columns not recognized → Fixed using Power Query data type conversion
- Profit Margin calculation → Created DAX measure using DIVIDE()
- Choosing meaningful KPIs → Focused on revenue, profit, orders, regions, and products

📁 Files in Repository
- Superstore_sales_dashboard.pbix – Power BI dashboard file
- Superstore_Sales_Dashboard_Writeup.pdf – Project documentation
- README.md – Project overview

🏁 Conclusion
This project demonstrates hands-on experience in data cleaning, DAX calculations, interactive dashboard design, and business insight generation using Power BI. It is suitable as a portfolio project for Data Analyst / BI roles.
