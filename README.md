# Customer Churn Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](PASTE_YOUR_COLAB_LINK_HERE)

## Project Overview

Customer churn is a critical business challenge for subscription-based companies because retaining existing customers is often significantly less expensive than acquiring new ones. This project develops a machine learning pipeline to predict whether a telecom customer is likely to churn based on customer demographics, account information, contract details, and service usage patterns.

The project follows a complete end-to-end machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and business interpretation. Three classification algorithms, Logistic Regression, Random Forest, and Gradient Boosting, were trained and compared to identify the most effective model for churn prediction.

## Dataset

**Dataset:** Telco Customer Churn Dataset

* Source: Kaggle
* Records: 7,043 customers
* Features: 21 columns
* Target Variable: `Churn`

  * 0 = Retained Customer
  * 1 = Churned Customer

The dataset contains customer demographics, tenure information, subscription services, contract types, payment methods, monthly charges, and total charges.

## Key Findings

* **Gradient Boosting achieved the best overall performance**, delivering a ROC-AUC score of **0.8429** and an accuracy of **76%**, outperforming both Logistic Regression and Random Forest.
* **Monthly charges were strongly associated with churn behavior**. Churned customers paid an average of **$74/month**, compared to **$61/month** for retained customers, suggesting that higher-paying customers are more likely to leave.
* **Contract type emerged as a major churn driver**, with month-to-month customers showing substantially higher churn rates than customers on one-year and two-year contracts, highlighting the importance of long-term customer retention strategies.

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub
