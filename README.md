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


2. **Install requirements**
(if not using Colab)

pip install -r requirements.txt


4. **Run the notebook**
  .Open churn_model.ipynb in Jupyter or Google Colab
  .Run all cells and follow instructions


---

##🧪 **Model Performance**
The notebook includes:

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Feature Importance chart

✅ Model tuning and evaluation using cross-validation

---

##💡 **Future Ideas**
Deploy model using Streamlit

Add a real-time prediction form

Use Flask API + React frontend

Train with larger telecom datasets
