📌 Project Overview

This project aims to predict customer churn for SyriaTel, a leading telecom provider. The goal is to develop a machine learning model that identifies customers likely to leave and provides actionable insights to improve customer retention strategies.

📊 Business Understanding

🔍 Problem Statement

Customer retention is a major challenge in the telecommunications industry. High churn rates lead to revenue loss and increased customer acquisition costs. By analyzing customer behavior, SyriaTel aims to:

Predict customer churn (Yes/No) using a classification model.

Identify key factors influencing churn.

Provide insights to enhance customer retention strategies.

📂 Data Understanding

🔹 Dataset Overview

The dataset consists of 3,333 customer records with 21 attributes, including:

Customer demographics: State, area code.

Usage metrics: Call minutes (day/evening/night), charges.

Service-related attributes: International plan, voice mail plan, customer service calls.

Target variable: Churn (Yes/No).

🛠️ Data Cleaning & Feature Engineering

✔️ Steps Taken

Handling Missing Values: No missing values were found.

Feature Selection: Dropped phone number as it is irrelevant.

Categorical Encoding: Converted categorical variables (international plan, voice mail plan) to numerical values (0/1).

Outlier Treatment: Used the Interquartile Range (IQR) method to cap extreme values.

Scaling: Standardized numerical features for better model performance.

📈 Exploratory Data Analysis (EDA)

Key Findings:

Customers with higher customer service call frequency are more likely to churn.

International plan subscribers have a higher churn rate.

High total day minutes usage slightly reduces churn.

🤖 Machine Learning Models

🏆 Models Implemented

Logistic Regression (Baseline Model)

Decision Tree Classifier

Random Forest Classifier

Hyperparameter Tuned Models (Random Forest & Decision Tree)

📊 Performance Metrics

Accuracy

Precision, Recall, F1-score

AUC-ROC Score

Model                  Accuracy                   AUC-ROC
Logistic Regression    85.9%                       0.60

Decision Tree          90.6%                       0.79

Random Forest           92.9%                      0.80

Tuned Decision Tree     93.1%                      0.83

Tuned Random Forest    92.9%                       0.80

📌 The Tuned Decision Tree model performed the best, providing strong predictive accuracy and interpretability.

📢 Business Recommendations

Enhance Customer Service: Reduce customer dissatisfaction by improving service quality.

Review International Plans: Adjust pricing and quality to better serve customers.

Proactive Outreach: Identify high-risk customers early and offer incentives to retain them.

Deploy the Decision Tree Model: Integrate the model into SyriaTel’s CRM to predict churn and guide retention strategies.

🎯 Conclusion

This project successfully identified key churn factors and built an effective predictive model. Implementing the insights and recommendations can help SyriaTel reduce churn and improve customer satisfaction.

📌 Developed by: [Your Name]📅 Date: March 2025💡 Technologies Used: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Machine Learning
