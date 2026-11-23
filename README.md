# Customer Churn & Retention Analytics

An end-to-end data analytics and machine learning project exploring customer churn patterns, identifying retention opportunities, and predicting customer churn using Python, SQL, and Tableau.

## Project Overview

This project analyses customer subscription and usage data from a Peloton-inspired fitness platform to understand the factors associated with customer churn.

The project covers data cleaning, SQL-based business analysis, exploratory data analysis, feature engineering, machine learning, model evaluation, and interactive Tableau dashboards.

## Business Objectives

- Understand customer churn patterns across subscription plans and customer segments.
- Identify behavioural and business factors associated with customer churn.
- Analyse customer engagement and usage patterns.
- Develop machine learning models to predict customer churn.
- Translate analytical findings into actionable retention insights.

## Tools & Technologies

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **SQL:** Business analysis and customer segmentation
- **Machine Learning:** Scikit-learn, Logistic Regression, Random Forest, Gradient Boosting, HistGradientBoosting
- **Visualisation:** Tableau Public
- **Environment:** Google Colab

## Project Workflow

1. Data loading and initial exploration
2. Data cleaning and validation
3. Customer-level feature engineering
4. SQL-based business analysis
5. Exploratory data analysis
6. Churn prediction problem formulation
7. Data preprocessing and train-test splitting
8. Model development and validation
9. Model comparison and selection
10. Model interpretation and evaluation
11. Exporting analytical results for Tableau

## Key Business Insights

- Overall customer churn rate: **42.10%**.
- Monthly subscribers had a churn rate of **51.18%**, compared with **26.38%** for annual subscribers.
- Customers who churned had lower average monthly workouts (2.94) than retained customers (4.90).
- Customers who churned averaged 88.31 active minutes per month, compared with 147.25 for retained customers.
- The most frequently reported cancellation reason was not using the platform enough (32.24% of churned customers).

## Machine Learning

The prediction task focuses on identifying customers likely to churn within the next three months.

The modelling dataset contains 3,161 customers, with 10 selected features.

Models explored:
- Logistic Regression
- Random Forest
- Gradient Boosting
- HistGradientBoosting

### Final Model Performance

The Random Forest model was selected based on validation F1-score.

| Metric | Random Forest |
|---|---:|
| Accuracy | 0.701 |
| Precision | 0.354 |
| Recall | 0.814 |
| F1-score | 0.493 |
| ROC-AUC | 0.827 |
| Average Precision | 0.519 |

The final Random Forest classification threshold was 0.40.

## Tableau Dashboards

Explore the interactive dashboards:

**[View Customer Churn & Retention Analytics on Tableau Public](https://public.tableau.com/app/profile/sneha.v2952/viz/Customer_Churn_And_Retention_Analytics/Dashboard1)**

The project includes three dashboards:

1. Customer Churn & Retention Analytics
2. Customer Engagement & Usage Analysis
3. Churn Prediction & Model Insights

Dashboard screenshots are available in the `screenshots/` folder.

## Repository Structure

```text
Customer-Churn-Retention-Analytics/
│
├── notebooks/
│   └── Customer_Churn_Analytics.ipynb
│
├── screenshots/
│   └── Dashboard screenshots
│
└── README.md
```

## Key Takeaways

This project demonstrates an end-to-end analytical workflow, combining business analysis, exploratory data analysis, machine learning, model evaluation, and data visualisation to derive insights into customer churn and retention.


