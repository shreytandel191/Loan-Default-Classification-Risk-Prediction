# Loan Default Classification & Risk Prediction
## Project Overview
This project aims to predict the likelihood of loan default using historical data from Lending Club—one of the largest peer-to-peer lending platforms in the U.S. The goal is to build a machine learning model that helps financial institutions assess credit risk before issuing a loan, thereby reducing losses and improving portfolio quality.

## Business Objective
Lending institutions face significant losses when borrowers default. Identifying high-risk borrowers at the time of loan application enables smarter lending decisions.
This project helps answer key business questions:

1. Who is likely to default on a loan?
2. What borrower or loan characteristics are associated with higher risk?
3. How can machine learning be used to improve credit assessment?

## Tools & Technologies Used
* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
* Jupyter Notebook for analysis and prototyping
* EDA for pattern and outlier detection
* Feature Engineering to improve model performance
* Machine Learning Models: Logistic Regression, Random Forest, XGBoost
* Imbalanced Learning: SMOTE (Synthetic Minority Over-sampling)
* Model Evaluation: Accuracy, Precision, Recall, ROC-AUC

## Project Workflow
1. **Problem Understanding:** Define objective and business impact of predicting defaults.
2. **Data Cleaning:** Handle missing values, drop irrelevant columns, and parse date fields.
3. **Exploratory Data Analysis (EDA):** Understand key trends in borrower behaviour, loan purpose, credit history, etc.
4. **Preprocessing & Feature Engineering:** Encode categorical variables, scale numerical fields, and engineer relevant features (e.g., credit utilisation ratio).
5. **Model Building:** Train and tune multiple classifiers; handle class imbalance using SMOTE.
6. **Model Evaluation:** Compare performance using confusion matrix, ROC-AUC, and other metrics.
7. **Insights & Recommendations:** Share business-level conclusions from model predictions.


## Key Findings
* Borrowers with low annual income, poor credit history, and high debt-to-income ratios are significantly more likely to default.
* XGBoost provided the best performance with a ROC-AUC score of ~0.89.
* The model can effectively assist lending companies in flagging high-risk loan applications early in the process.

## Conclusion
This project demonstrates how machine learning can transform traditional risk assessment models in the lending industry. With proper data and predictive tools, financial institutions can significantly reduce default rates and make smarter, data-driven lending decisions.
