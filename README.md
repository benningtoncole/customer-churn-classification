Customer Churn Classification

Predicting customer churn using machine learning classification models.

📌 Overview

This project builds and evaluates classification models to predict customer churn using the Telco Customer Churn dataset (7,043 customers).

The goal is to identify key drivers of churn and provide actionable business insights to improve customer retention.

🛠 Tools & Technologies
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Logistic Regression
Random Forest
ROC-AUC Analysis
📊 Model Performance
Logistic Regression (Scaled)
Accuracy: 0.81
Precision: 0.65
Recall: 0.60
F1 Score: 0.62
AUC: 0.84
Random Forest
Accuracy: 0.80
Precision: 0.64
Recall: 0.54
F1 Score: 0.58

Logistic Regression performed best overall and demonstrated strong discriminatory power (AUC = 0.84).

🔍 Key Insights

Factors increasing churn risk:

Fiber optic internet
Electronic check payment method
Higher total charges

Factors reducing churn risk:

Longer tenure
One-year and two-year contracts
Customers with dependents
Tech support and online security services
📈 Business Impact
Enables proactive identification of high-risk customers
Supports targeted retention campaigns
Improves customer lifetime value
Reduces revenue loss from attrition
🚀 Future Improvements
Cross-validation tuning
Gradient Boosting / XGBoost comparison
SHAP analysis for deeper explainability
Deployment via Streamlit or Flask