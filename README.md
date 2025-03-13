# Customer Churn Prediction - SyriaTel

##  Project Overview  
Customer churn is a critical issue in the telecom industry, leading to revenue loss and high acquisition costs. This project aims to develop a **machine learning model** to predict customer churn for **SyriaTel**, enabling proactive retention strategies.

---

##  Business Understanding  

###  Problem Statement  
Customer retention is more cost-effective than acquiring new users. High churn rates impact revenue, making it essential to:  

- **Predict churn (Yes/No) using machine learning.**  
- **Identify key factors contributing to churn.**  
- **Provide actionable insights to enhance customer retention.**  

---

##  Data Understanding  

###  Dataset Overview  
The dataset consists of **3,333 customer records** with **21 attributes**, including:

- **Demographics:** State, area code  
- **Usage Metrics:** Call minutes (day/evening/night), charges  
- **Service Attributes:** International plan, voice mail plan, customer service calls  
- **Target Variable:** Churn (Yes/No)  

---

##  Data Preprocessing & Feature Engineering  

- **Missing Values:** No missing values found.  
- **Feature Selection:** Dropped irrelevant columns (e.g., phone number).  
- **Categorical Encoding:** Converted categorical variables into numerical (0/1).  
- **Outlier Treatment:** Used **IQR method** to cap extreme values.  
- **Scaling:** Standardized numerical features for optimal model performance.  

---

##  Exploratory Data Analysis (EDA)  

### Key Findings:  
- Customers with **more than 4 customer service calls** are highly likely to churn.  
- Users with an **international plan** exhibit a **higher churn rate**.  
- Higher **daytime call minutes usage** correlates with **lower churn risk**.  

---

##  Machine Learning Models & Performance  

###  Models Implemented  
- **Logistic Regression** (Baseline)  
- **Decision Tree Classifier**  
- **Random Forest Classifier**
-  **KNN Classifier**  
- **Hyperparameter Tuned Models** (Decision Tree & Random Forest)  

### Model Performance  

| Model                | Accuracy | AUC-ROC Score |
|----------------------|---------|--------------|
| Logistic Regression | 85.9%   | 0.60         |
| Decision Tree       | 90.6%   | 0.79         |
| Random Forest       | 92.9%   | 0.80         |
| **Tuned Decision Tree** | **93.1%** | **0.83** |
| Tuned Random Forest | 92.9%   | 0.80         |

 **The Tuned Decision Tree model performed the best**, balancing **accuracy** and **interpretability**.  

---

##  Business Recommendations  

- **Enhance Customer Support:** Reduce churn by improving service quality for customers making frequent support calls.  
- **Reevaluate International Plans:** Modify pricing and features to increase customer satisfaction.  
- **Proactive Outreach:** Identify high-risk customers early and offer retention incentives.  
- **Deploy the Decision Tree Model:** Integrate it into SyriaTel’s CRM for real-time churn predictions.  

---

##  Conclusion  
By leveraging machine learning, this project successfully:  

✔ **Identified key churn factors**  
✔ **Developed an accurate prediction model**  
✔ **Provided actionable insights for reducing churn**  

Implementing these recommendations will help **SyriaTel** improve customer retention and optimize business growth. 

---

##  Developed by: Kelvin Ng'ola Mutuku  
 Date: March 2025  
 Technologies Used: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Machine Learning  

---
