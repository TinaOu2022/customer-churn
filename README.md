# Customer Churn Detector

The Jupter notebook code and detailed analysis is here: [Code](https://github.com/XinyanOu/customer-churn/blob/main/Telecom_Customer_Churn.ipynb)

### Background
This project focuses on **predicting customer behavior with the aim of enhancing customer retention.**

The dataset is from a telco company, which provides telephone and wireless services, as well as internet data and other related services. 
In the telecom industry, customers have the flexibility to choose from various service providers, leading to active switching between them. 
Customer churn is defined as that a customer discontinues the service within the last month. Customer churn causes a loss of revenue. 

Retaining existing customers proves to be much more cost-effective than acquiring new ones.
Therefore, the marketing team sends retention promotions to the potentially churning customers to retain them, but have problems efficiently finding the churning customers and the reasons why they churn.

### Objectives
- 1 . Predict whether a customer will churn next month;
- 2 . Figure out the factors resulting in customer churn.

### Context
In this project, a **Customer Churn Detector** is built based on binary classification models, and an **Insight Engine** for Marketing Team to generate sale strategies is developed.

- Exploratory Data Analysis(EDA) with data visualization is performed; 
- Feature Engineering is conducted, and two methods including SMOTE-ENN are used for imbalanced data handling; 
- Multiple classifiers are compared including Logistic Regression, Decision Tree, Random Forest, SVC, XGBoost, Gradient Boost; 
- Multiple metrics including recall, precision, f1, accuracy and roc_auc are compared for different bussiness purposes;
- Achieved a Recall score of 0.89 with XGBoost model, 3 times more effective than random choose to locate churning customers;
- Achieved a ROC_AUC score of 0.86 with Random Forest model, used SHAP to identify key factors, provided insights for marketing strategies;
- Model deployment is implemented to a Web App using Flask and GCP.




