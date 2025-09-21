# 📊 Sales Overview Dashboard

## 📌 Project Description

The **Sales Overview Project** is an analytical study of sales data aimed at tracking business performance, identifying trends, and generating insights to support management decisions. The project uses **Excel** for data processing and **Power BI** for creating interactive dashboards and visualizations.

---

## 🎯 Project Objective

- Analyze company sales data to identify revenue trends.
- Highlight top-selling products, regions, and subcategories.
- Provide actionable insights for business decisions.
- Track performance over time to support strategic planning.

---

## 🛠️ Tools & Technologies

- **Excel:** Used for data cleaning, validation, and ensuring dashboard data accuracy.
- **Power BI:** Used for dashboard creation and calculations using **DAX**.

---

## 📊 Data Source

- Dataset contains **4 years of sales data**.
- Includes product details, subcategories, regions, states, monthly sales, and profit.
- Data is **simulated** for demonstration and learning purposes.

---

## 📈 Dashboard Overview

### 1️⃣ Filter Panel

- Located at the top-left of the dashboard.
- Contains a **Year dropdown filter** (e.g., 2024) to view sales data for a specific year.
- Makes the dashboard **interactive**, allowing users to switch between years and explore trends over time.

---

### 2️⃣ Sales by Category (Donut Chart)

- Shows the **proportion of total sales contributed by each product category** (Technology, Office Supplies, Furniture).
- **Visually highlights** which categories generate the most revenue.
- **Total sales** are displayed in the center for quick reference.
- Uses **conditional formatting**:
  - Darker shades indicate higher sales.
  - Lighter shades indicate lower sales.

---

### 3️⃣ Sales by Region (Bar Chart)

- Horizontal bar chart showing **sales distribution across regions** (West, East, Central, South).
- Bars are shaded according to performance, making it easy to **spot high-performing and low-performing regions at a glance**.

---

### 4️⃣ Key Metrics (Top Cards)

- **Total Sales:** Shows the revenue generated in the selected year.
- **Total Profit:** Highlights net profit.
- **Total Orders:** Displays total sales transactions.
- **Year-over-Year Comparison:** Shows changes compared to the previous year (absolute numbers and percentage) with a **line chart under each card** representing the trend.

---

### 5️⃣ Sales Trend by Subcategory (Column Chart)

- Displays **sales for each product subcategory**, allowing analysis **by year, region, and category**.
- An **average sales line** helps identify subcategories performing **above or below average**.
- **Conditional formatting applied**:
  - Darker shades indicate subcategories performing above average.
  - Lighter shades indicate subcategories performing below average.
- Subcategory names are abbreviated (e.g., Appl, Bind, Chai); full names can be used in documentation for clarity.

---

### 6️⃣ Top 15 Performing States (Tree Map)

- Displays **sales distribution across states**, highlighting the **top 15 performing states** for the selected year.
- **Largest blocks** (e.g., California, New York) represent states with the highest sales contribution, while **smaller blocks** (e.g., Delaware, Kentucky) indicate lower contributions.
- **Tooltips provide detailed insights** for each state.

![Tooltip Screenshot](https://github.com/user-attachments/assets/58db73bc-8d62-4bfe-91e9-4c92db78f927)

- Tooltip details dynamically update based on **selected year, region, and category**, including:
  - **State:** Name of the state (e.g., California)
  - **Total Sales:** Amount for selected filters (e.g., $88K)
  - **% of Total:** Contribution to overall sales under selected filters (e.g., 19%)
  - **Rank:** Sales rank among all states (e.g., #1)
  - **Total Profit:** Net profit (e.g., $14K)
  - **Profit Margin:** Profit as a percentage of sales (e.g., 16%)
  - **Average Discount:** Discount offered (e.g., 7%)
  - **Quantity Sold:** Number of products sold (e.g., 1,498)
  - **Top Category:** Highest-selling product category (e.g., Furniture)
  - **Top Sub-Category:** Highest-selling product sub-category (e.g., Chairs)

---

### 7️⃣ Top Performing Subcategory (Bar Chart)

- Displays the **top 5 subcategories by sales revenue** in the dashboard.
  - Example: Phones ($105K), Chairs ($96K), Binders ($73K), Storage ($70K), Copiers ($63K)
- **Sales values are displayed inside each bar** for quick reference.
- Helps users **quickly identify the most profitable product types**.
- Works dynamically with **selected year, region, and category** filters.

---

### 8️⃣ Overall Insights

- **Top Contributors:** Highest revenue comes from **Technology category**, **Phones subcategory**, and **West region**.
- **Positive Growth:** Total sales, profit, and orders show **year-over-year improvement**, reflecting strong business performance.
- **Interactive Exploration:** Users can **filter by year, region, and category** to explore trends dynamically.
- **Visual Analysis with Consistent Colors:** Tree Map and charts use **three colors** (dark = high, medium = average, light = low) to highlight performance and identify patterns, trends, and areas needing attention.

---

### 🖼 Dashboard Screenshot

![Sales Dashboard](https://github.com/nagendra-gk/Sales-Overview/blob/main/DashboardImage.png)
