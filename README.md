# 🧠 Employee Attrition Prediction Using Machine Learning Models

## 📘 Overview
Employee attrition is a significant concern for many organizations, especially in the IT industry. This project uses **Machine Learning (ML)** techniques to predict whether an employee is likely to leave the company based on various features such as **job satisfaction**, **work-life balance**, **monthly income**, and **overtime**.

By applying data preprocessing, feature engineering, balancing techniques (SMOTE), and model comparison, this system identifies high-risk employees — helping HR departments take proactive retention actions.

---

## 🎯 Objectives
- Predict employee attrition using machine learning algorithms.  
- Analyze the most important features influencing employee turnover.  
- Compare multiple models and select the one with the best performance.  
- Assist HR professionals with data-driven insights.

---

## ⚙️ Methodology

Dataset Collection
↓
Data Preprocessing (Encoding & Cleaning)
↓
Balancing Data (SMOTE)
↓
Train/Test Split
↓
Model Training (LR, DT, RF, XGBoost)
↓
Model Evaluation
↓
Best Model Selection
↓
Final Prediction



### Key Steps:
1. **Data Cleaning & Preprocessing** — Encoding categorical variables using OneHotEncoder.  
2. **Balancing Dataset** — Using **SMOTE** to handle class imbalance.  
3. **Model Training** — Applying four models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
4. **Evaluation** — Using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.  
5. **Feature Importance Visualization** — Determining top factors influencing attrition.

---

## 📊 Dataset
- **Size:** 1000 records  
- **Features (X):** Age, Gender, Department, Education, JobRole, MonthlyIncome, DistanceFromHome, YearsAtCompany, JobSatisfaction, WorkLifeBalance, OverTime  
- **Target (Y):** Attrition (Yes/No)  
- **Train/Test Split:** 75% / 25%  
- **File:** `employee_attrition_IT_1000.csv`

---

## 🧩 Technologies Used
- **Language:** Python  
- **Libraries:**
  - `pandas`, `numpy`
  - `scikit-learn`
  - `xgboost`
  - `imbalanced-learn`
  - `matplotlib`, `seaborn`

---



### Feature Importance (XGBoost)
Top predictors influencing attrition:
- JobSatisfaction  
- WorkLifeBalance  
- OverTime  
- MonthlyIncome  
- YearsAtCompany  

## 🤖 Model Performance

| Model | Accuracy | Remarks |
|--------|-----------|----------|
| Logistic Regression |0.75 | 
| Decision Tree | 0.84 | 
| **Random Forest** |**0.899** | ✅ Best overall model | 
| XGBoost| 0.894 | 



