# Customer Churn Prediction - SyriaTel

## 📌 Project Overview  
Customer churn is a major challenge in the telecom industry, leading to revenue loss and high acquisition costs. This project leverages machine learning to predict customer churn for SyriaTel, enabling proactive retention strategies.

---

## 📊 Business Understanding  

### 🔍 Problem Statement  
Customer retention is more cost-effective than acquiring new users. High churn rates impact revenue, making it essential to:  

- Predict churn (Yes/No) using machine learning.  
- Identify key factors contributing to churn.  
- Provide actionable insights to enhance customer retention.  

---

## 📂 Data Understanding  

### 🔹 Dataset Overview  
The dataset consists of 3,333 customer records with 21 attributes, including:

- Demographics: State, area code  
- Usage Metrics: Call minutes (day/evening/night), charges  
- Service Attributes: International plan, voice mail plan, customer service calls  
- Target Variable: Churn (Yes/No)  

---

## 🛠 Data Preprocessing & Feature Engineering  

- Missing Values: No missing values found.  
- Feature Selection: Dropped irrelevant columns (e.g., phone number).  
- Categorical Encoding: Converted categorical variables into numerical (0/1).  
- Outlier Treatment: Used IQR method to cap extreme values.  
- Scaling: Standardized numerical features for optimal model performance.  

---

## 📈 Exploratory Data Analysis (EDA)  

### Key Findings:  
- Customers with more than 4 customer service calls are highly likely to churn.  
- Users with an international plan exhibit a higher churn rate.  
- Higher daytime call minutes usage correlates with lower churn risk.  

---

## 🤖 Machine Learning Models & Performance  

### 🏆 Models Implemented  
- Logistic Regression (Baseline)  
- Decision Tree Classifier  
- Random Forest Classifier  
- KNN Classifier  
- SVM Classifier  
- Neural Network Classifier  
- Naive Bayes Classifier  
- Hyperparameter Tuned Models (Decision Tree & Random Forest)  

### Model Performance  

| Model                  | Accuracy | F1-Score |
|------------------------|---------|----------|
| Logistic Regression   | 85.8%   | 29.8%    |
| Decision Tree         | 90.2%   | 66.1%    |
| Random Forest        | 93.2%   | 69.2%    |
| Tuned Decision Tree | 94.3% | 77.9%  |
| Tuned Random Forest | 93.0% | 66.7%  |
| Neural Network       | 88.2%   | 49.5%    |
| SVM                  | 86.6%   | 8.3%     |
| KNN                  | 85.3%   | 10.2%    |
| Naive Bayes          | 57.8%   | 27.8%    |

📌 The Tuned Decision Tree model performed the best, balancing **accuracy* and *interpretability.  

---

## 📢 Business Recommendations  

- Enhance Customer Support: Reduce churn by improving service quality for customers making frequent support calls.  
- Reevaluate International Plans: Modify pricing and features to increase customer satisfaction.  
- Proactive Outreach: Identify high-risk customers early and offer retention incentives.  
- Deploy the Tuned Decision Tree Model: Integrate it into SyriaTel’s CRM for real-time churn predictions.  
- Regular Model Updates: Retrain the model periodically to maintain accuracy.  
- Monitor Key Metrics: Track customer service calls and international plan subscriptions for potential churn risks.  

---

## 🎯 Conclusion  
By leveraging machine learning, this project successfully:  

✔ Identified key churn factors  
✔ Developed an accurate prediction model  
✔ Provided actionable insights for reducing churn  

Implementing these recommendations will help SyriaTel improve customer retention and optimize business growth. 🚀  

---

## 📌 Developed by: christine nzili kindena  
📅 Date: March 2025  
💡 Technologies Used: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Machine Learning  

---
