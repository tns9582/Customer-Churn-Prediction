# Customer-Churn-Prediction
Predicting telecom customer churn using Logistic Regression.

##Project Overview

This project analyzes data from a telecommunications company, consisting of 7,043 customer records and multiple features across demographics, account details, and service usage.


Key Steps:

Data Cleaning: Handled missing values, standardized data, and transformed features into binary formats.

EDA: Visualized churn patterns across demographics, billing, tenure, and service usage.

Modeling: Built and evaluated a Logistic Regression model using:

One-Hot Encoding for categorical variables

StandardScaler for numerical features

80/20 Train-Test Split

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC


Key Insights

✅ Customers with month-to-month contracts, paperless billing, and fiber optic internet are more likely to churn.

✅ Short tenure and higher monthly charges strongly correlate with churn behavior.

✅ The model achieved:

Accuracy: 82%

ROC-AUC: 0.86

High precision for non-churners, moderate recall for churners (room for improving sensitivity)



Strategic Recommendations

Target At-Risk Customers: Especially those with high TotalCharges and short tenure.

Enhance Fiber Optic Offerings: Improve service quality to retain dissatisfied users.

Boost Retention: Promote long-term contracts with incentives and loyalty programs.

Early Engagement: Improve onboarding and follow-up during the first 3 months.


Tools & Techniques

Data Visualization: Matplotlib, Seaborn

Machine Learning Framework: Scikit-learn

ML Algorithms & Concepts:
Logistic Regression
Classification
Model Evaluation (Confusion Matrix, Precision, Recall, F1-Score)
Data Preprocessing (Label Encoding, Feature Scaling, Train-Test Split)
Hyperparameter Tuning
Cross-Validation


Conclusion

This project successfully demonstrates how logistic regression can be used to predict customer churn with strong accuracy and actionable insights. By identifying key churn indicators—such as contract type, tenure, and monthly charges— I enable businesses to proactively target at-risk customers and enhance retention strategies.

