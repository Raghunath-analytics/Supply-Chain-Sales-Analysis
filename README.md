## 🏁 Project Objective

The goal of this project is to analyze and visualize sales data from a supply chain to identify key performance metrics, trends, and business insights. This dashboard supports business decision-making by answering strategic questions around sales, profits, orders, and customer behavior.

## 📝 Project Description

This Power BI-based interactive dashboard provides a comprehensive overview of sales performance across different years, regions, categories, and shipping modes. The visualizations enable users to drill down into:
- Total orders and sales trends
- Top-performing products
- Regional profitability
- Category-wise performance
- Year-over-year (YoY) growth
- Customer discounts and returns
- Profitability metrics per user

  ## 📁 Data Source
<a href="https://github.com/Raghunath-analytics/Supply-Chain-Sales-Analysis/blob/main/Supply-Chain-Dataset.xlsx">Dataset</a>

## 📌 Refined Business Questions
- What is the total number of customer orders processed during the reporting period?
- Which five products generated the highest total sales revenue?
- Which geographical region recorded the highest overall profit?
- What are the total sales figures segmented by product category and sub-category?
- What is the year-over-year (YoY) sales growth percentage?
- What was the total sales value for the previous month?
- How does monthly sales performance compare to the previous month using a trend line analysis?
- What is the average discount percentage offered across each product category?
- What are the profit margins expressed as a percentage across different categories or sub-categories?
- What is the total discount value offered during the reporting period?
- What is the average profit earned per customer?

 ## 📊 Dashboard Preview
   <a href="https://github.com/Raghunath-analytics/Supply-Chain-Sales-Analysis/blob/main/Dashboard.jpeg">Dashboard</a>

## 🧰 Tools & Techniques Used
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query Editor**
- **Excel as a data source**

## 🔄 Process Followed
1. **Data Collection**: Extracted from Excel-based sales reports.
2. **Data Cleaning**: Removed duplicates, handled nulls, formatted data types in Power Query.
3. **Data Modeling**: Created relationships among Sales, Products, Customers, and Date tables.
4. **DAX Calculations**: Built KPIs and metrics using DAX measures.
5. **Visualization**: Designed interactive visuals like line charts, bar charts, maps, and cards.
6. **Dashboard Layout**: Used bookmarks, slicers, and filters for user interaction.

## 🚧 Challenges Faced
- Inconsistent date formats impacting time intelligence calculations.
- Managing complex relationships between multiple tables.
- Optimizing DAX queries for performance with large datasets.
- Designing an intuitive user interface within limited screen space.

## 🔮 Future Insights and Recommendations
- **Forecasting**: Integrate time-series forecasting for predictive sales analytics.
- **Customer Segmentation**: Identify customer lifetime value and segment for marketing strategies.
- **Inventory Optimization**: Include stock levels vs sales data to reduce over/understocking.
- **Dynamic Tooltips**: Add advanced tooltips for improved user interactivity.
- **Mobile Optimization**: Redesign for mobile-friendly performance tracking.

## ✅ Final Conclusions
This dashboard has successfully answered key business questions including:

1. **Total Orders**: 787
2. **Top 5 Products**: Canon imageCLASS, Fellowes Paper Shredder, Cubify Cube, Hewlett Packard Printer, GBC DocuBind
3. **Highest Profit Region**: West (inferred from sales density map)
4. **Sales by Category**: Technology (139K), Furniture (111K), Office Supplies (101K)
5. **YOY Growth**: -1.00%
6. **Previous Month Sales**: 37K (from December to January)
7. **Monthly Sales Line Chart**: Displays growth trend with visible increases in Q4
8. **Average Discount %**: 0.16
9. **Profit Margin % by Subcategory**: Ranges from 0.15 to 0.44
10. **Total Discount Given**: 253.17
11. **Average Profit Per Customer**: 99.13

This project empowers stakeholders with actionable insights to enhance performance, reduce returns, and refine strategies.
