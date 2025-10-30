# Super-Store-Sales-Dashboard
An interactive Power BI Dashboard that visualizes sales performance, profitability, and customer insights for a Super Store dataset. The dashboard enables data-driven decision-making by highlighting key sales trends, product performance, and regional profitability.
📊 Dashboard Overview
🔹 Key Metrics
Total Sales: ₹1.56M
Total Profit: ₹192.89K
Total Quantity Sold: 25K units
Average Discount: 0.16
🔹 Highlights
Top Performing Categories: Technology & Furniture
Most Profitable Sub-Categories: Phones & Copiers
Highest Profit Region: West (≈33% of total profit)
Peak Sales Month: December — strong seasonal demand
Customer Insights: Key customers such as Sean Miller and Tamara Chand contribute significant sales.
🧠 Key Insights
💰 Technology and Furniture categories dominate total sales.
🏆 Phones & Copiers deliver the highest profit margins.
🌎 West Region leads in profitability.
📈 December shows the highest sales — ideal for promotional campaigns.
🚚 Multiple shipping modes analyzed (First Class, Second Class, Standard, Same Day).
👥 Segmentation across Consumer, Corporate, and Home Office customers.
🗂️ Dashboard Components
Section	Description
KPI Cards	Display Total Sales, Quantity, Profit, and Average Discount
Profit by Sub-Category (Treemap)	Visualizes profit contribution of each product sub-category
Sales by Category (Bar Chart)	Compares overall sales between Technology, Furniture, and Office Supplies
Sales by Month (Line Chart)	Tracks monthly sales trends to identify seasonal patterns
Profit by Region (Pie Chart)	Shows profit percentage by region (East, West, Central, South)
Customer Performance Table	Lists top customers and their total sales
Map Visualization	Displays city-wise sales distribution across regions
Filters	Allow analysis by Ship Mode, Segment, and Date Range
⚙️ Tools & Technologies
Power BI Desktop / Power BI Service
Data Source: Super Store Sales Dataset (CSV or Excel)
Techniques Used:
Data Cleaning & Transformation (Power Query)
DAX Measures for KPIs (Total Sales, Profit, Discount, Quantity)
Hierarchical and cross-filtered visualizations
Dynamic date filters and slicers
🧩 DAX Measures Used
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Quantity = SUM(Sales[Quantity])
Average Discount = AVERAGE(Sales[Discount])

📈 Insights Summary
Metric	Observation
Sales Trend	Rises sharply in Q4 (November–December)
Regional Profit	West Region contributes ≈33%
Category Comparison	Technology leads with ~₹0.56M sales
Customer Distribution	Concentrated in high-spending cities
Discount Analysis	Low discounts correlate with higher profit
📂 Repository Structure
📦 Super-Store-Sales-Dashboard
 ┣ 📊 SuperStore_Dashboard.pbix     # Power BI file
 ┣ 📄 Superstore_Sales_Data.xlsx     # Dataset (if applicable)
 ┣ 🖼️ Screenshot.png                 # Dashboard preview image
 ┗ 📘 README.md                      # Project documentation

🚀 How to Use
Clone or download this repository.
Open the .pbix file in Power BI Desktop.
Load or connect your dataset if required.
Explore filters, visual interactions, and insights.
🧾 Author



Created by: [Deepali rai]
Tool: Power BI
Purpose: Data Analysis & Visualization Portfolio Project
