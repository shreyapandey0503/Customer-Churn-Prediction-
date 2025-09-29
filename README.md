<H1> Customer-Churn-Prediction </H1>
<br>

 **The Problem We Are Solving**
The goal of this project is to proactively identify customers who are at a high risk of "churning"—canceling their service with a telecom company. By predicting churn, the company can take targeted actions to retain valuable customers before they leave.

<br>
<br>

**Our Process**
We followed a structured data science workflow:
1.  **Data Exploration & Cleaning:** We started with a dataset of over 7,000 customers. We cleaned the data, handled missing values, and used visualizations (bar charts and histograms) to understand the initial relationships between customer attributes and churn.
2.  **Feature Engineering:** We created new, more insightful features from the existing data. For example, we grouped customers by their tenure ('New', 'Established', 'Loyal') and created a flag for customers who lacked key security services.
3.  **Model Building:** We preprocessed the data and trained three different machine learning models (Logistic Regression, Random Forest, and XGBoost) to see which could most accurately predict churn based on the patterns it learned.

<br>
<br>

**Our Key Findings & Outcome**
Our analysis revealed several key drivers of customer churn:
* **Contract Type:** Customers on a **month-to-month contract** are significantly more likely to leave than those on one or two-year contracts.
* **Internet Service:** Customers with **fiber optic internet** showed a higher churn rate, suggesting potential issues with price or service quality.
* **Tenure:** Newer customers with a **short tenure** are at the highest risk.

The final outcome is a predictive model (XGBoost) that can identify at-risk customers with over **80% accuracy**. This model provides the business with a powerful tool to focus its retention efforts, such as offering loyal discounts or targeted support, to the customers who need it most.
