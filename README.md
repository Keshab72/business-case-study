# Project Report: Analysis of Sales Data

**Introduction:**
The objective of this project is to analyze sales data from the provided dataset, "Business Case Study.csv". The dataset contains information about orders, customers, products, sales, and profits. The analysis aims to provide insights into sales performance, profitability, and customer segments.

**Data Source:**
The dataset used for analysis is "Business Case Study.csv". It contains various columns such as Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit.

**Analysis:**

1. **Data Preprocessing:**
   - The dataset was loaded using Pandas, and initial exploration showed that there were no missing values.
   - The Order Date and Ship Date columns were converted to datetime format to facilitate time-based analysis.
   - Additional columns for Order Month, Order Year, and Order day of the week were created from the Order Date column.

2. **Monthly Sales Analysis:**
   - The total sales were calculated for each month, and a line plot was generated using Plotly to visualize the monthly sales trend. It was observed that the maximum sales occurred in November.

3. **Sales by Category:**
   - The total sales were aggregated by category (Furniture, Office Supplies, Technology), and a donut chart was created to show the distribution of sales across categories. Technology emerged as the category with the highest sales.

4. **Monthly Profit Analysis:**
   - The total profit was calculated for each month, and a line plot was generated to visualize the monthly profit trend. The maximum profit was observed in December.

5. **Profit by Category:**
   - The total profit was aggregated by category, and a donut chart was created to show the distribution of profit across categories. Technology emerged as the category with the highest profit.

6. **Sales and Profit by Customer Segment:**
   - The total sales and profit were aggregated by customer segment (Consumer, Corporate, Home Office), and a bar chart was generated to visualize the sales and profit for each segment. It was observed that the Consumer segment had the highest sales and profit.

**Conclusion:**
The analysis of the sales data provides valuable insights into sales performance, profitability, and customer segments. The findings can be used by businesses to make informed decisions regarding product offerings, marketing strategies, and customer targeting.

**Note:**
The code for data preprocessing and analysis is provided in both PDF and CSV formats for reference. The project repository on GitHub contains the dataset, code files, and this report for further exploration and collaboration.
