# Automated A/B Testing Analysis Tool & BI Dashboard

An advanced product analytics project focused on automating statistical significance calculations for e-commerce conversion funnels using Python and building a dynamic A/B testing monitor in Tableau.

## 📂 Project Deliverables
* **Jupyter Notebook:** 👉 **[View Python Statistical Script](./AB_Testing_Automation.ipynb)**
* **Interactive Dashboard:** 👉 **[View Live Tableau A/B Tool](https://public.tableau.com/views/AB-testingwiththedeterminationofthestatisticalsignificance/AB-testingwiththedeterminationofthestatisticalsignificance?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
* **Processed Data:** 👉 **[View Calculated Statistical Results (.csv)](./ab_test_stat_results.csv)**

## 🎯 Project Objectives & Methodology

### 1. Statistical Automation via Python (Google Colab)
* **Dynamic Architecture:** Developed a scalable Python script using arrays and loops to dynamically compute statistical significance across an unlimited number of product metrics, eliminating reliance on manual online calculators.
* **Funnel Metrics Analyzed:** Automated p-value and statistical significance calculations for four critical conversion steps:
  * `add_payment_info / session` (Payment Conversion)
  * `add_shipping_info / session` (Shipping Conversion)
  * `begin_checkout / session` (Checkout Initiation)
  * `new_accounts / session` (User Registration Rate)
* **Granular Segmentation:** Expanded the analysis beyond totals to evaluate test variations across multiple dimensions, including experiment IDs, geographic regions (countries), and user device types.

### 2. BI Dashboard Integration & Verification (Tableau)
* **Custom UI/UX Design:** Redesigned an interactive, high-performance executive dashboard with a unique color palette and optimized layout to track experiment performance.
* **Visual Anchors for Significance:** Integrated the processed Python dataset into Tableau to visually highlight where metric shifts were **statistically significant** vs. where changes occurred due to random noise.
* **Advanced Features:** Implemented dynamic filtering by Experiment ID and embedded clear documentation detailing the underlying mathematical logic used by the Python backend.

## 🛠️ Tech Stack & Methods
* **Programming & Libraries:** Python (Pandas, NumPy, SciPy.stats, Statsmodels)
* **Business Intelligence:** Tableau Public
* **Statistical Framework:** Hypothesis Testing, Two-Sample Proportion Tests (Z-test / Chi-Square), p-value evaluation, Statistical Power, and Confidence Intervals.

