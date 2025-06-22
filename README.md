# 🧠 Customer Churn Prediction using Olist E-Commerce Data

This project aims to predict customer churn for an e-commerce business using the Olist dataset (Brazil). We use transaction, payment, and customer behavior data to identify churn risk and provide business recommendations.

---

## 📦 Dataset

**Source**: [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- Orders, customers, payments, and product data from a large e-commerce platform in Brazil
- Used to build insights and predict customer churn

---

## 🎯 Project Goals

- Define customer churn using behavioral data
- Analyze patterns between churned and retained customers
- Build a model to predict future churn
- Provide actionable business strategies for retention

---

## 🔧 Tools & Skills Demonstrated

- **Data Cleaning & Processing** (pandas, datetime handling)
- **Exploratory Data Analysis** (matplotlib, seaborn)
- **Feature Engineering for Churn**
- **Classification Models** (Logistic Regression, Random Forest)
- **Evaluation Metrics** (Precision, Recall, F1, ROC-AUC)

---

## | Notebook                         | Description                                                                   |
| -------------------------------- | ----------------------------------------------------------------------------- |
| `01_data_loading_cleaning.ipynb` | Load and clean raw data                                                       |
| `02_churn_labeling.ipynb`        | Define churn based on customer behavior (e.g. inactivity)                     |
| `03_feature_engineering.ipynb`   | Engineer features like number of orders, total payment, and recency           |
| `04_modeling_churn.ipynb`        | Train and evaluate classification models (Logistic Regression, Random Forest) |
| `05_results_visualization.ipynb` | Visualize model performance (confusion matrix, metrics comparison)            |

---

## 🚀 Getting Started

To run the project locally:

```bash
git clone https://github.com/YOUR_USERNAME/churn-prediction-olist.git
cd churn-prediction-olist
pip install -r requirements.txt
jupyter notebook
