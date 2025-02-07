# E-commerce-Data-analytics
E-commerce Data Analytics Project

Answered Question:
1. Identified the monthly sales trends and determined the months with the highest and lowest sales.
2. Evaluated sales performance across product categories to find the best and worst-performing categories.
3. Conducted a detailed sales analysis based on sub-categories.
4. Reviewed the monthly profit data to determine the most profitable month.
5. Assessed the profit distribution across different categories and sub-categories.
6. Examined sales and profit variations across customer segments.
7. Calculated the sales-to-profit ratio for better financial insights.

Exploratory Data Analysis on the Superstore Dataset

The Superstore dataset contains transaction records from a retail business, covering aspects such as order details, customer information, product categories, sales, discounts, and profits. This dataset is useful for business analytics, sales forecasting, and customer segmentation.

Data Exploration & Preprocessing
Dataset Loading & Initial Inspection

The dataset is loaded into a Pandas DataFrame and displayed using .head() to check the first few rows.
The .info() method reveals that all 21 columns have non-null values, meaning there are no missing values to handle.
The .describe() function provides statistical insights, highlighting key sales and profit trends.
Key Observations from the Summary Statistics:

The Sales column shows a wide range, with values from $0.44 to $22,638.48.
The Profit column contains negative values, indicating that some sales resulted in losses.
The Discount varies from 0% to 80%, which could influence profitability.
The dataset contains over 9,994 transactions, making it suitable for visualization and further analysis.

Next Steps & Visualization
With Plotly imported, the next steps in analysis could include:
Sales Trends Over Time: Plotting sales against order dates to identify seasonal trends.
Profitability by Category & Region: Using bar charts or heatmaps to understand which product categories and locations generate the most revenue and profit.
Customer Segmentation: Analyzing sales patterns based on customer segments to optimize marketing strategies.

Conclusion
This dataset provides valuable insights into sales performance, customer behavior, and business efficiency. By applying data visualization and advanced analytics, we can uncover trends and optimize business decisions.
