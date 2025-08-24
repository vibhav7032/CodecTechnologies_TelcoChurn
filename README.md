# Telco Customer Churn Prediction

## 📌 Project Overview
This project was developed as part of my **Summer Internship** at **Codec Technologies** (June 26, 2025 – August 25, 2025).  
The goal of this project is to **predict telecom customer churn** using machine learning techniques.  
Churn refers to customers discontinuing their service, and predicting it helps telecom companies reduce losses by implementing retention strategies.

---

## 🎯 Key Highlights
- Performed **data cleaning and preprocessing** on Telco Customer Churn dataset.
- Conducted **exploratory data analysis (EDA)** to identify churn patterns.
- Built **machine learning pipelines** using Scikit-learn for consistent preprocessing and modeling.
- Applied **hyperparameter tuning** with GridSearchCV for model optimization.
- **Gradient Boosting Classifier** achieved:
  - ROC-AUC: **0.839**
  - Accuracy: **79%**
  - Precision (Churn): 0.64 | Recall (Churn): 0.52 | F1: 0.57
- Saved the final pipeline using `joblib` for future predictions.

---

## 📊 Key Insights from EDA
- **Churn Rate**: ~26% of customers churned.
- **Tenure**: Longer-tenured customers are less likely to churn.
- **Contract Type**: Month-to-month customers are most likely to churn.
- **Payment Method**: Manual payment methods correlate with higher churn.
- **Service Add-ons**: Lack of security or tech support increases churn risk.

---

## 📝 Notes
- The dataset file `Telco-Customer-Churn.csv` is stored in the main directory for direct access.
- The Jupyter Notebook `Telco-Customer-Churn.ipynb` is self-contained and can be run independently.
- The file `telco_churn_pipeline.pkl` contains the **trained Gradient Boosting pipeline** for inference.

---

## 🏢 Internship Details
- **Organization**: Codec Technologies  
- **Role**: Data Science Intern  
- **Duration**: June 26, 2024 – August 25, 2024  
- **Skills Applied**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Machine Learning, Model Deployment

---

## 📬 Contact
Feel free to reach out via **GitHub** for any feedback or questions.

---
