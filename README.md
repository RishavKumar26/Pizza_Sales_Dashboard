# Pizza_Sales_Dashboard
## Interactive Pizza Sales Insight Dashboard
A visually rich, interactive dashboard designed to uncover key patterns in pizza sales—highlighting best-selling categories, order timing trends, size preferences, and top-performing pizzas to support data-driven decision-making in food retail.
## Short Description / Purpose
The SliceWise Pizza Sales Dashboard is an interactive Excel report designed to analyze and visualize key trends in pizza sales data. It highlights total revenue, peak order times, best- and worst-selling pizzas, and sales distribution by category and size—enabling restaurant managers and analysts to make informed business and marketing decisions.
## 🚀 Tech Stack

The dashboard was built leveraging the following tools and technologies to support data extraction, transformation, visualization, and user interaction:

- 📊 **Microsoft Excel** – Served as the primary platform for data analysis, visualization, and dashboard creation.  
- 📌 **PivotTables & PivotCharts** – Used to aggregate sales data and generate dynamic, interactive visualizations.  
- 🔄 **Slicers & Timelines** – Implemented for intuitive filtering based on order dates, categories, and time-based trends.  
- 🧹 **Excel Formulas** – Employed functions such as `TEXT`, `IF`, and `VLOOKUP` for data cleaning, formatting, and transformation.  
- 🖼️ **Visual Design Elements** – Customized layouts, color schemes, and background images to enhance user engagement and interpretability.  
- 🧾 **SQL Queries** – Utilized to extract and preprocess pizza sales data from a relational database before importing it into Excel for analysis.  
- 📁 **File Format** – The final report was delivered in `.xlsx` format, suitable for sharing, modification, and offline use.  

## 📂 Data Source and Structure

- **Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/), specifically from a publicly available fictional pizza sales dataset designed for data analysis and dashboarding practice.

- **Overview**:  
  It contains detailed transactional data from a pizza restaurant, with each row representing a unique pizza item within an order.

- **Key Fields**:  
  `pizza_id`, `order_id`, `total_orders`, `pizza_name_id`, `quantity`, `order_date`, `order_date_new`,  
  `order_day`, `order_time`, `order_time_new`, `unit_price`, `total_price`,  
  `pizza_size`, `pizza_category`, `pizza_ingredients`, and `pizza_name`.

- **Analysis Capability**:  
  This structure enables in-depth analysis of:
  - Order patterns  
  - Time-based sales trends  
  - Pricing and revenue  
  - Product performance  
  - Customer preferences

- **Format**:  
  The dataset is organized in a **flat table format**, making it well-suited for:
  - Time-series analysis  
  - Category breakdowns  
  - Interactive Excel dashboard visualizations

## 📊 Pizza Sales Dashboard Explanation

### 🔍 Business Problem
In the competitive quick-service restaurant industry, especially among pizzerias, it can be difficult to monitor product performance, understand customer ordering behavior, and pinpoint high-revenue time slots. Without a data-driven approach, businesses risk missing key opportunities to optimize menus, staffing, and promotional strategies.

---

### 🎯 Goal of the Dashboard
The dashboard aims to deliver an interactive, visual summary of pizza sales performance. It highlights:
- Sales by pizza category and size  
- Top and bottom-selling pizzas  
- Order trends across days and hours  
- Peak sales periods  

This tool is designed to support restaurant managers, analysts, and decision-makers in making strategic and operational improvements based on real-time data insights.

---

### 📈 Walkthrough of Key Visuals

- **Total Revenue, Average Order Value, Orders**  
  High-level KPIs to assess overall business health.

- **Daily Trends (by Day and Hour)**  
  Identifies peak ordering times, aiding in resource and staff planning.

- **Sales by Category and Size**  
  Highlights which types and sizes of pizzas contribute most to sales.

- **% of Sales by Category & Size (Donut Charts)**  
  Visual breakdown of sales distribution across product lines.

- **Top 5 & Bottom 5 Sellers**  
  Showcases best- and worst-performing pizzas to guide menu adjustments.

- **Interactive Timeline Filter**  
  Enables filtering of all visuals by date range for focused, time-based analysis.

---

### 💡 Business Impact & Insights

- **Peak Sales Timing**:  
  Friday and Saturday evenings see the highest order volumes—useful for staffing and marketing.

- **Top Performers**:  
  The **Classic** category and **Large-sized** pizzas contribute the most to revenue.

- **Product Performance**:  
  **Chicken** and **Hawaiian pizzas** are top sellers, while certain niche items underperform—informing inventory and promotional strategies.

- **Strategic Value**:  
  Empowers the business to refine pricing, optimize inventory levels, and enhance menu offerings using data-backed decisions.

