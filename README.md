# Customer Churn Analysis

## Project Overview
This project provides a comprehensive exploratory data analysis (EDA) of a telecommunications customer dataset. The objective is to identify key drivers of customer attrition and provide actionable insights to improve customer retention strategies.

---

# Problem Statement
Explain:
* What problem is being solved: High customer turnover (churn) impacting long-term revenue.
* Why it matters: Retaining existing customers is significantly more cost-effective than acquiring new ones.
* Real-world/business relevance: This analysis helps decision-makers identify high-risk segments and tailor loyalty programs.

---

# Project Objectives
*   **Clean and Preprocess** raw customer data for analysis.
*   **Analyze Demographic Trends** to see how age (Senior Citizen) and gender impact retention.
*   **Evaluate Service Usage** to determine which features (Internet, Security, Support) correlate with loyalty.
*   **Assess Financial Drivers** such as contract types, payment methods, and monthly charges.
*   **Visualize Findings** to make data-driven recommendations.

---

# Dataset Information
*   **Source:** External CSV via Google Drive
*   **Size:** 7,043 rows, 21 columns
*   **Target Variable:** `Churn` (Yes/No)
*   **Key Features:** `tenure`, `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`, `SeniorCitizen`, and service flags.

---

# Tech Stack
*   **Python**
*   **Pandas**
*   **NumPy**
*   **Matplotlib**
*   **Seaborn**

---

# Project Workflow
1.  **Data Collection**: Loading the dataset via direct URL.
2.  **Data Cleaning**: Correcting data types (specifically `TotalCharges`) and handling zero-tenure records.
3.  **Exploratory Data Analysis**: 
    *   Univariate analysis of the target variable.
    *   Bivariate analysis of categorical and numerical features against churn.
4.  **Feature Engineering**: Transforming binary numeric flags into descriptive categories for clear visualization.
5.  **Visualization**: Creating complex subplots and percentage-based comparisons.

---

# Key Insights
*   **Retention Risk**: Approximately **26.54%** of the customer base has left the service.
*   **Contractual Loyalty**: Month-to-month contracts are the strongest predictor of churn, while long-term contracts ensure stability.
*   **Critical Window**: The first 5 months of tenure are the most volatile for new customers.
*   **Digital Friction**: Customers utilizing Electronic Checks churn at significantly higher rates than those using automated payment methods.

---

# Visualizations
*   **Churn Percentage**: Pie chart showing the overall distribution of churn.
*   **Demographic Risks**: Stacked bar charts highlighting a 41.7% churn rate among Senior Citizens.
*   **Tenure Density**: Histogram showing the distribution of customer longevity.
*   **Service Matrix**: A grid of 9 count plots evaluating specific product offerings.

---

# Folder Structure
```bash
Customer_Retention_Project/
│── data/ 
│── notebooks/
│   └── retention_analysis.ipynb
│── README.md
│── requirements.txt
```

# Installation & Usage
```bash
pip install pandas numpy matplotlib seaborn
```
Run the notebook cells in order to reproduce the analysis and visualizations.

# Future Improvements
*   Implement Machine Learning models (Logistic Regression, Random Forest) for predictive churn scoring.
*   Perform feature importance analysis to quantify the exact weight of each driver.
*   Develop a Streamlit dashboard for real-time customer risk monitoring.

# Learning Outcomes
*   Advanced data cleaning and type conversion in Pandas.
*   Statistical visualization using Seaborn's categorical plotting tools.
*   Interpreting business metrics from raw behavioral data.

# Resume-Ready Project Description
*   Executed a deep-dive Exploratory Data Analysis (EDA) on 7,000+ customer records to identify key behavioral drivers of churn.
*   Designed and implemented data cleaning pipelines to resolve formatting inconsistencies in financial columns, ensuring 100% data accuracy for analysis.
*   Uncovered critical business insights regarding contract types and payment methods, providing a data-driven foundation for customer retention strategies.
*   Developed high-impact visualizations including stacked bar charts and service matrices to communicate findings to stakeholders.


