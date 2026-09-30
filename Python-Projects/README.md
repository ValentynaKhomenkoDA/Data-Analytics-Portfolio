This folder contains a comprehensive end-to-end data analytics project developed in Google Colab (Jupyter Notebook), focusing on retail data cleaning, integration, and business performance analysis.

## 🐍 Project Overview
* **Project Name:** Global Retail Sales Performance Analysis
* **Objective:** Cleaned, integrated, and analyzed a multi-table global retail dataset (sales events, product profiles, and country regions) to extract actionable business insights on sales trends, profitability, and logistics efficiency.
* **Source Code:** 👉 **[View Jupyter Notebook](./sales_analysis.ipynb)**

## 📊 Key Analytical Phases Completed
* **Data Cleansing & Integrity:** Handled missing values, corrected data types, eliminated duplicates (including hidden spaces and cross-alphabet encodings), and addressed data anomalies.
* **Data Integration:** Merged relational schemas (`events.csv`, `products.csv`, `countries.csv`) into a single denormalized dataframe for performance optimization.
* **Core Business Metrics:** Computed global high-level KPIs including total order volume, gross revenue, net profit, and geographic market reach.
* **Multi-Dimensional Sales Analysis:** Analyzed and visualized income/profit dynamics segmented by Product Categories, Geography (Countries/Regions), and Sales Channels (Online vs. Offline).
* **Logistics & Shipping Analytics:** Evaluated lead time (the duration between order placement and shipment) across categories and regions, analyzing its correlation with final profit margins.
* **Time-Series & Seasonality Trends:** Tracked long-term sales dynamics and identified weekly purchase patterns and product seasonality using day-of-week parsing.

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Data Manipulation & Processing:** Pandas, NumPy
* **Data Visualization & Insights:** Matplotlib, Seaborn
