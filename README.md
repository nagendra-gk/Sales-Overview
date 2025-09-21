📊 Sales Overview Power BI Dashboar
📌 Project Description

The Sales Overview Project is an analytical study of sales data to track business performance, identify trends, and generate insights for management decisions. The project uses Excel for data processing and Power BI for interactive dashboards and visualizations.


🎯 Project Objective

Analyze company sales data to identify revenue trends.

Highlight top-selling products, regions, and subcategories.

Provide actionable insights for business decisions.

Track performance over time to support strategic planning.


🛠️ Tools & Technologies

Excel – Used for data cleaning and checking values to ensure the dashboard data is accurate.

Power BI – Used for dashboard creation and performing all calculations using DAX.


📊 Data Source

Dataset contains 4 years of sales data

Includes product details, subcategories, regions, states, monthly sales, and profit.

Data is simulated for demonstration purposes and learning analytics techniques.


📈 Dashboard Overview
1️⃣ Filter Panel

Contains a Year dropdown filter (e.g., 2024) that allows users to view sales data for a specific year.

Makes the dashboard interactive, so users can easily switch between different years to see trends over time.




2️⃣ Sales by Category (Donut Chart)

Shows the proportion of total sales contributed by each product category.

Categories in this example: Technology, Office Supplies, Furniture.

The chart visually highlights which categories generate the most revenue.

Uses conditional formatting:

Darker shades represent categories with higher sales.

Lighter shades represent categories with lower sales.

Total sales are displayed in the center for quick reference.


3️⃣ Sales by Region (Bar Chart)

Horizontal bar chart showing sales distribution across regions (e.g., West, East, Central, South).

Bars are visually shaded to reflect sales performance, making it easy to spot high-performing and low-performing regions at a glance.


4️⃣ Key Metrics (Top Cards)

Total Sales: Shows the revenue generated in the selected year.

Total Profit: Highlights net profit.

Total Orders: Displays total sales transactions.

Year-over-Year Comparison: Shows the change compared to the previous year (absolute numbers and percentage) with a line chart under each card representing the trend.



5️⃣ Sales Trend by Subcategory (Column Chart)

Displays sales for each product subcategory, allowing analysis by year, region, and category to see how each subcategory performs across different segments.

An average sales line helps identify which subcategories are performing above or below average.

Conditional formatting is applied:

Darker shades indicate subcategories performing above average.

Lighter shades indicate subcategories performing below average.

Subcategory names are abbreviated (e.g., Appl, Bind, Chai); you can use full names in documentation for clarity.


6️⃣ Top 15 Performing States (Tree Map)

Displays sales distribution across states, highlighting the top 15 performing states for the selected year.

Largest blocks (e.g., California, New York) represent states with the highest sales contribution, while smaller blocks (e.g., Delaware, Kentucky) indicate lower contributions.

Tooltips provide detailed insights for each state.

<img width="281" height="183" alt="TooltipScreenshot" src="https://github.com/user-attachments/assets/58db73bc-8d62-4bfe-91e9-4c92db78f927" />

When you hover over a state in the Tree Map, the tooltip displays detailed information for that state based on the selected year, region, and category:

State: Name of the state (e.g., California).

Total Sales: Total sales amount for the selected filters (e.g., $88K).

% of Total: Percentage contribution of this state to overall sales under the selected filters (e.g., 19%).

Rank: Sales rank of the state among all states for the selected filters (e.g., #1).

Total Profit: Net profit generated from sales in the state (e.g., $14K).

Profit Margin: Profit as a percentage of sales (e.g., 16%).

Average Discount: Average discount offered on products sold in that state (e.g., 7%).

Quantity Sold: Total number of products sold in that state (e.g., 1,498).

Top Category: Product category with the highest sales in that state (e.g., Furniture).

Top Sub-Category: Product sub-category contributing the most sales (e.g., Chairs).

This tooltip dynamically updates according to the selected year, region, and category, helping users quickly analyze performance across different segments.



7️⃣ Top Performing Subcategory (Bar Chart)

Displays the top 5 subcategories by sales revenue in the dashboard.

Sales values are shown inside each bar for quick reference.

Helps users quickly identify the most profitable product types and focus on high-performing items.

Works dynamically with selected year, region, and category, so users can see top subcategories under different filters.


8️⃣ Overall Insights

Top Contributors: Highest revenue comes from Technology category, Phones subcategory, and the West region.

Positive Growth: Total sales, profit, and orders all show year-over-year growth, reflecting strong business performance.

Interactive Exploration: The dashboard allows users to filter by year, region, and category, making it easy to explore trends dynamically.

Visual Analysis: Tree Map and charts provide a clear view of patterns, trends, and areas needing attention, helping stakeholders make informed decisions quickly.






![Sales Dashboard](https://github.com/nagendra-gk/Sales-Overview/blob/main/DashboardImage.png)
