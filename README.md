# telco-customer-churn-prediction
# 📞 Telco Customer Churn Prediction

This project focuses on predicting customer churn for a telecommunications company using machine learning techniques. The model predicts whether a customer is likely to leave the service based on their demographic and service usage data.

The project also includes an interactive **Streamlit web application** for real-time predictions.

---

# 📊 Project Summary

| Component           | Technology / Technique   | Purpose                                            |
| ------------------- | ------------------------ | -------------------------------------------------- |
| Model               | Random Forest Classifier | Predicts if a customer will churn (Yes/No)         |
| Imbalance Handling  | SMOTEENN (imblearn)      | Handles class imbalance in dataset                 |
| Deployment          | Streamlit                | Provides a web interface for predictions           |
| Feature Engineering | One-Hot Encoding         | Converts categorical variables into numeric format |

---

# 📂 Dataset

The dataset contains telecom customer information such as:

* Gender
* Senior Citizen
* Tenure
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges

Target Variable:

**Churn**

---

# ⚙️ Machine Learning Pipeline

1️⃣ Data Cleaning
2️⃣ Exploratory Data Analysis
3️⃣ Feature Engineering
4️⃣ Handling Imbalanced Data using **SMOTEENN**
5️⃣ Model Training using **Random Forest**
6️⃣ Model Evaluation
7️⃣ Model Deployment using **Streamlit**

---

# 🚀 Quick Start Guide

Install dependencies

```
pip install -r requirements.txt
```

Run the application

```
streamlit run app.py
```

---

# 📁 Key Files

```
app.py                 → Streamlit web application
model.pkl              → Trained Random Forest model
Model_Building.ipynb   → ML model training pipeline
churn_analysis_EDA.ipynb → Data analysis notebook
tel_churn.csv          → Dataset
```

---

# 📌 Result

The model predicts whether a telecom customer is likely to churn and provides prediction confidence using a deployed Streamlit application.
