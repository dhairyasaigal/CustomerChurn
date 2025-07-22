# 🎯 Customer Churn Prediction

Predict which customers are likely to leave using machine learning — so you can take action **before it's too late**!


## 📌 About the Project

This project focuses on predicting customer churn — identifying which customers are at risk of leaving a service. It's a classification problem solved using multiple ML algorithms.

We use:
- 📂 Real-world customer data
- 🧠 Machine learning models (like Random Forest, XGBoost)
- 📊 Visualization & evaluation tools
- ⚖️ SMOTE to handle class imbalance

---

## 🛠️ Tools & Technologies

- **Python** – Core language
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – ML algorithms and preprocessing
- **XGBoost** – Boosting model
- **SMOTE** – Oversampling for imbalanced datasets

---

## 📁 Folder Structure

customer-churn-prediction/
├── churn_model.ipynb # Main notebook
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv # Dataset
└── README.md # Project overview


---

## 📊 Dataset Used

📌 **Dataset Name**: *Telco Customer Churn Dataset*  
📥 **Source**: [IBM Sample Datasets](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/)  
📄 **Filename**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

### ✅ Dataset Features Include:
- Customer ID
- Gender, SeniorCitizen, Partner, Dependents
- Tenure, MonthlyCharges, TotalCharges
- Contract type (Month-to-month, One year, Two year)
- Internet service, Streaming services, Tech support
- Payment method, Paperless billing, etc.
- Target: `Churn` (Yes/No)

The dataset contains **7,043 customer records** and is ideal for binary classification problems.

---

## 🚀 Getting Started

1. **Clone this repo**  
   ```bash
   git clone https://github.com/dhairyasaigal/customer-churn-prediction.git
   cd customer-churn-prediction


