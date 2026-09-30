# End-to-End E-commerce Sales & Traffic Analytics

A comprehensive data analytics project that spans the entire data pipeline: extracting relational web and sales data via SQL, performing exploratory and advanced statistical analysis in Python, and building an interactive executive dashboard in Tableau.

## 📂 Project Deliverables
* **Jupyter Notebook:** 👉 **[View Python & SQL Analysis Notebook](./E_commerce_Analytics.ipynb)**
* **Interactive Dashboard:** 👉 **[View Live Tableau Dashboard](https://public.tableau.com/shared/NHKSJWY4C?:display_count=n&:origin=viz_share_link)**

## 🎯 Project Objectives & Phase Highlights

### 1. Data Extraction & Architecture (SQL & BigQuery)
* Connected to **Google BigQuery** database via Python backend.
* Wrote optimized SQL queries using complex `JOIN` logic to merge multi-table schemas (sessions, traffic sources, user registries, and product catalogs).
* Preserved data integrity by using correct join types to ensure all orders and sessions were captured, including guest (unregistered) user journeys.

### 2. Exploratory Data Analysis & Integrity (Python)
* Performed deep data profiling (datetime boundaries, structural missing values analysis, unique session identification).
* Evaluated demographic and performance leaders (Top 3 continents, Top 5 countries, Top 10 product categories).
* Analyzed user acquisition funnels, device market share (%), traffic distribution, and email marketing conversion metrics (subscription and verification rates).

### 3. Time-Series & Trend Analysis (Python)
* Visualized global MoM/YoY sales dynamics and diagnosed hidden seasonality.
* Conducted multi-dimensional trend analysis to evaluate revenue distribution by device types, traffic channels, and core regions (America, Europe, Asia).

### 4. Advanced Statistical Analysis (Python)
* **Correlation Metrics:** Analyzed the statistical significance of relationships between session volumes and gross sales, cross-continental market performance, and top product category dependencies.
* **Hypothesis Testing (A/B Testing logic):** Conducted rigorous statistical testing to find differences between groups:
  * Compared buying behavior between registered and non-registered users (distribition analysis & non-parametric/parametric testing).
  * Evaluated session volumes across varying traffic channels.
  * Performed proportion tests to identify differences in organic traffic share between Europe and America.

### 5. BI Dashboard & Storytelling (Tableau)
* Built a sleek, 2-page interactive business dashboard deployed on **Tableau Public** for executive data storytelling.

## 🛠️ Tech Stack & Methods
* **Data Warehousing:** SQL, Google BigQuery
* **Programming & Libraries:** Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy / Statsmodels)
* **Business Intelligence:** Tableau Public
* **Statistical Methods:** Pearson/Spearman Correlation, p-value verification, T-test / Mann-Whitney U test, Chi-Square / Proportion tests.

