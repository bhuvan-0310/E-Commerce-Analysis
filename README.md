# Data Analyst Portfolio — Marketing Analytics

---

## Executive Report

### Page 1 — Project Overview & Methodology

**Objective:**
This project demonstrates a comprehensive approach to *marketing analytics* using **SQL, Python, and Power BI**. The aim is to extract, clean, analyze, and visualize marketing campaign and customer data to derive actionable insights for business decision-making.

**Tools & Technologies:**

* **SQL** — data extraction, transformations, joins, aggregations.
* **Python** — data cleaning, EDA, feature engineering, predictive modeling.
* **Power BI** — interactive dashboards and visual storytelling.

**Workflow:**

1. **Data Ingestion:** SQL scripts extract relevant customer, transaction, and campaign data from databases.
2. **Cleaning & Transformation:** Python scripts handle missing values, normalize formats, and engineer new features (e.g., customer lifetime value, churn risk).
3. **Exploratory Data Analysis (EDA):** Python notebooks generate statistical summaries and visualizations to identify trends.
4. **Segmentation & Modeling:** Machine learning models (clustering, regression) highlight customer segments and predict key metrics.
5. **Dashboarding:** Power BI dashboards bring together KPIs (conversion rates, ROI, customer retention) for stakeholders.

**Repository Structure:**

```
├── data/         # Raw & processed datasets
├── sql/          # SQL queries
├── notebooks/    # Python notebooks
├── python/       # Python scripts
├── powerbi/      # Power BI dashboards
└── docs/         # Supporting documentation
```

### Page 2 — Insights, Outcomes & Recommendations

**Key Insights Derived:**

* **Channel Effectiveness:** Social media channels drove the highest conversion rates, while email campaigns yielded the lowest CPA (cost per acquisition).
* **Customer Segments:** Identified 3 high-value customer clusters based on purchase frequency and average spend. These segments represent \~40% of revenue but only 25% of customers.
* **Campaign Performance:** Seasonal campaigns showed strong ROI in Q4, suggesting budget reallocation during holiday periods could maximize returns.
* **Cohort Analysis:** New customer retention after 3 months dropped significantly for specific cohorts, signaling the need for improved onboarding
