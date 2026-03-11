# Customer Churn Prediction

Week 1 & Week 2: EDA + Machine Learning Models

## 📌 Course Information

Course: Introduction to Applied Artificial Intelligence  
Semester: BS 8th Semester  
Project: Customer Churn Prediction  
Author: Aliha Batool  
Date: 11/03/2026  

---

## 📊 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) and building predictive models on the Telco Customer Churn dataset.

Goals:

- Understand customer behavior patterns  
- Identify factors contributing to churn  
- Build machine learning models to predict churn  
- Discover high-risk customer groups  
- Prepare actionable business insights  

---

## 📂 Dataset Information

Source: Telco Customer Churn Dataset (Kaggle)

Total Customers: 7,043  
Total Features: 21  
Target Variable: Churn (Yes/No)

⚠️ Note: The dataset file (customer_data.csv) is not included in this repository. Please download it from Kaggle and place it in the project folder before running the notebooks.

---

## 📁 Repository Structure

week1-eda.ipynb → Exploratory Data Analysis notebook  
week2-ml-models.ipynb → Machine learning models for churn prediction  
README.md → Project documentation  
.gitignore → Excludes unnecessary files  

---

## 🔍 Key Insights

### Week 1: EDA

- Customers with month-to-month contracts have significantly higher churn rates.  
- Customers with short tenure (< 6 months) are more likely to churn.  
- Higher Monthly Charges are associated with increased churn.  
- Fiber optic internet users show higher churn compared to DSL users.  
- Customers using electronic check payment method have higher churn rates.  

### Week 2: ML Models

Trained and compared three machine learning models:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Evaluated models using Accuracy, Classification Report, and Confusion Matrix.

Conducted feature engineering with new features:

- TotalRevenue = tenure × monthly charges  
- TotalServices = count of active services  
- TenureGroup = binned tenure  
- HighCharges = flag for high monthly charges  

Retrained the best model (Random Forest) with new features.

Observed improvement in prediction accuracy after feature engineering.

---

## 📊 Typical Model Accuracy (Expected Ranges)

| Model | Accuracy Range |
|------|---------------|
| Logistic Regression | 75–80% |
| Decision Tree | 72–78% |
| Random Forest | 78–83% |

---

## ⭐ Top Important Features (Typical)

- Contract type (month-to-month indicator)  
- Tenure (how long customer has been with company)  
- Monthly Charges  
- Internet Service type  
- Payment Method  

---

## ⚙️ Setup Instructions

Install required libraries:
Run the notebooks:
jupyter notebook week1-eda.ipynb
jupyter notebook week2-ml-models.ipynb
---

## 🚀 Next Steps

Week 3: Hyperparameter tuning and model optimization  
Explore additional feature combinations  
Handle class imbalance if needed  

---

## 🎯 Learning Outcomes

Through this project, I developed skills in:

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Data visualization using Matplotlib and Seaborn  
- Building and comparing machine learning models (Logistic Regression, Decision Tree, Random Forest)  
- Evaluating model performance metrics  
- Feature engineering for improved predictions  
- Identifying business insights from data  
- Git and GitHub version control workflow  

---

## 📬 Contact

GitHub: abhwork8
