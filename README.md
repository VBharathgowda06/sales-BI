# V.BHARATH POWER BI PROJECT

## 📊 Project Title:
ECOMMERCE Sales and Performance Dashboard (Power BI)

## 👨‍💻 Developed By:
V. Bharath  
Bachelor of Engineering in Artificial Intelligence and Data Science  
Mysore University School of Engineering, Manasagangotri  

## ❓ Problem Statement:
Businesses often struggle to gain real-time, data-driven insights from raw sales data spread across different regions, products, and time periods. Without visual analytics, identifying trends, top-performing categories, and regional variations becomes difficult, resulting in missed business opportunities and poor strategic decisions.

This project aims to solve that by creating an interactive Power BI dashboard that visualizes sales, profit, and performance metrics in a clear and actionable format. It enables stakeholders to monitor trends, analyze key performance indicators, and make informed decisions.

## 🧾 Description:
This Power BI project visualizes and analyzes key sales and performance metrics using an interactive dashboard. It enables stakeholders to make data-driven decisions by providing insights into revenue trends, regional performance, product success, and sales distribution.

## 📌 Features:
- Sales overview by region, product, and category
- Revenue and profit analysis with dynamic time filtering
- Monthly and yearly trend visualizations
- Key Performance Indicators (KPIs) for Sales, Profit, Quantity
- Top-performing products and customer segments
- Interactive slicers and drill-down functionality

## 🖼️ Dashboard Preview:
![Screenshot 2025-05-01 123642](https://github.com/user-attachments/assets/74154167-3de4-47c4-a7ed-872f0d68a551)


## 📂 Included File(s):
- `V.BHARATH POWER BI 1.pbix` – Power BI dashboard file

## 🛠️ Tools & Technologies Used:
- Microsoft Power BI Desktop
- Power Query Editor for data cleaning and shaping
- DAX (Data Analysis Expressions) for custom calculations and KPIs
- Interactive visuals: bar charts, line graphs, slicers, and cards

## 📈 Use Cases:
- Track sales performance across different time periods
- Identify high-performing products and categories
- Monitor profitability and business growth
- Present data-driven insights to management

## 🧭 How to Use:
1. Open the `.pbix` file using Power BI Desktop.
2. Explore the dashboard visuals and interact using slicers.
3. Filter by year, segment, or category for focused insights.
4. Hover over visuals for detailed tooltip information.
5. Export visuals if required for reports or presentations.

## 🔍 Sample DAX Measures Used:
- Total Sales = SUM(Sales[SalesAmount])
- Total Profit = SUM(Sales[Profit])
- Sales Trend = CALCULATE([Total Sales], DATESYTD(Sales[Date]))
- Top Products = RANKX(ALL(Products[ProductName]), [Total Sales], , DESC)

## 📞 Contact:
For queries or collaborations, feel free to contact:  
📧 vbharathgowda10@gmail.com  
📱 +91-9353206078

