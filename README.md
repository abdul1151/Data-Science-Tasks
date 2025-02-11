# **Machine Learning Projects - Loan Default, Disease Diagnosis, and Employee Attrition Prediction**

## **Project Overview**

This repository contains three machine learning classification projects implemented using **Streamlit**:

1. **Employee Attrition Prediction** - Predict whether an employee will leave a company based on HR data.
2. **Disease Diagnosis Prediction** - Predict the likelihood of diseases (e.g., diabetes) based on medical data.
3. **Loan Default Prediction** - Predict whether a loan applicant will default using financial data.

Each project follows a structured approach, including **EDA (Exploratory Data Analysis)**, **feature engineering**, **model training**, **evaluation**, and **explainability using SHAP**.

---

## **Project 1: Employee Attrition Prediction**

### **Objective:**

Develop a classification model to predict employee attrition and provide HR insights to reduce turnover.

### **Dataset:**

IBM HR Analytics Dataset

### **Steps Involved:**

1. **EDA** - Analyze employee demographics, job roles, and attrition trends.
2. **Feature Engineering** - Encode categorical variables, handle missing values.
3. **Model Training** - Train models like **Random Forest** and **Logistic Regression**.
4. **Model Evaluation** - Use **SHAP** to interpret feature importance.
5. **HR Recommendations** - Provide actionable strategies to reduce employee turnover.

### **How to Run:**

```bash
streamlit run app.py
```

---

## **Project 2: Disease Diagnosis Prediction**

### **Objective:**

Build a model to predict diseases such as **diabetes or heart disease** based on medical records.

### **Dataset:**

PIMA Diabetes Dataset or Heart Disease Dataset

### **Steps Involved:**

1. **EDA** - Explore relationships between features and disease outcome.
2. **Feature Selection & Scaling** - Normalize numerical features.
3. **Model Training** - Train **Gradient Boosting, SVM, Neural Networks**.
4. **Evaluation** - Use **F1 Score, AUC-ROC** to assess performance.
5. **Healthcare Insights** - Use **SHAP** to explain model decisions.

### **How to Run:**

```bash
streamlit run app.py
```

---

## **Project 3: Loan Default Prediction**

### **Objective:**

Develop a predictive model to assess **loan applicants' risk** and minimize lender losses.

### **Dataset:**

Lending Club Loan Dataset ("loans\_full\_schema.csv")

### **Steps Involved:**

1. **Data Preprocessing** - Handle missing values, encode categorical features.
2. **Class Imbalance Handling** - Use **SMOTE** to balance the dataset.
3. **Model Training** - Train **LightGBM and SVM** classifiers.
4. **Evaluation** - Measure **Precision, Recall, F1 Score**.
5. **Lender Insights** - Generate recommendations to reduce defaults.

### **How to Run:**

```bash
streamlit run app.py
```

---

## **Installation & Setup**

### **Dependencies:**

Ensure you have the required libraries installed before running the projects:

```bash
pip install streamlit pandas numpy scikit-learn seaborn matplotlib shap imbalanced-learn lightgbm
```

### **Run the Applications:**

Run each Streamlit application separately using:

```bash
streamlit run <filename.py>
```

For example:

```bash
streamlit run app.py
```

---

## **Project Insights & Contributions**

✅ **HR Strategy Improvement:** Employee Attrition project helps HR professionals retain employees.

✅ **Healthcare Analytics:** Disease Diagnosis project provides interpretable medical predictions.

✅ **Financial Risk Management:** Loan Default project helps lenders mitigate financial risks.

This repository demonstrates how **Machine Learning and Explainable AI (XAI)** can provide valuable insights across various industries.

---

##

