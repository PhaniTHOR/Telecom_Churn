# Predicting which customers are at high risk of churn

## Problem Statement

One of the major challenges faced by telecom companies is customer churn, which is the loss of customers to competitors. Customer churn is costly for telcos, as they have to spend more money on acquiring new customers than retaining existing ones. Moreover, customer churn reduces the profitability and loyalty of telcos. Therefore, telcos need to identify the customers who are at risk of churning and take proactive actions to prevent them from leaving. This can be done by using data analysis and machine learning techniques to predict customer churn and offer personalized incentives and services to retain them.

## Project Overview:
The project focuses on predicting customer churn in the telecom industry. Customer churn, or the loss of customers to competitors, is a significant challenge for telecom companies. The goal is to leverage data analysis and machine learning techniques to identify customers at risk of churning and implement proactive measures to retain them.

## Dataset Description:
The dataset contains information about customers, including services they've signed up for, account details, and demographic information.
Columns include customer churn status, services, account information, and demographic details.
Key Steps in the Analysis:
1. Exploratory Data Analysis (EDA) and Data Preprocessing:
Explored the dataset's structure, checked for missing values, and visualized distributions of key variables.
Transformed categorical variables, handled missing values, and encoded categorical features using dummy variables.
Scaled numerical features using different scaling methods (StandardScaler, MinMaxScaler, RobustScaler).
2. Hypothesis Testing:
Conducted hypothesis testing to assess relationships between variables.
Tested hypotheses related to average tenure, total charges, payment methods, contracts, and their associations with churn.
3. Model Building and Evaluation:
Implemented several machine learning models, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting Machines, Naive Bayes (Multinomial, Gaussian, Bernoulli), and Support Vector Classifier (SVC).
Evaluated models based on ML model score, recall, ROC/AUC curve values, and cross-validation scores.
Model Performance Summary:
Gradient Boosting Machines (GBM) emerged as the top-performing model, exhibiting high scores across all metrics.
Logistic Regression, Decision Tree, Random Forest, and Support Vector Classifier (SVC) also demonstrated competitive performance.
Naive Bayes models (Multinomial, Gaussian, Bernoulli) showed slightly lower performance compared to other models.
Conclusion:
The project concludes that Gradient Boosting Machines is the most suitable model for predicting customer churn in the telecom dataset. The thorough exploration of the dataset, careful preprocessing, and a variety of model evaluations contribute to the robustness of the analysis.

Recommendations:
The Gradient Boosting Machines model can be deployed for real-time predictions of customer churn.
Proactive measures, personalized incentives, and services can be implemented for customers identified as high-risk for churn.
Regular monitoring and updates to the model may be necessary as customer behaviors and preferences evolve.
The project provides a comprehensive approach to addressing the telecom industry's challenge of customer churn, offering actionable insights and a reliable predictive model for business decision-making.
