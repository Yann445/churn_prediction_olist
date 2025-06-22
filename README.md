# 🧠 Customer Churn Prediction using Olist E-Commerce Data

This project focuses on predicting customer churn in an e-commerce context using real-world transactional data from **Olist**, a major Brazilian online marketplace. It involves data cleaning, churn definition, feature engineering, model building, and performance visualization — all aimed at identifying which customers are likely to stop purchasing and how we can retain them.

---

## 📦 Dataset

**Source**: [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset includes:
- Orders, customers, payments, sellers, products, and reviews data
- Customer-level transactional behavior over time

---

## 🎯 Project Goals

- Define customer churn using behavioral data (e.g. recent inactivity)
- Explore patterns that separate churned vs. active customers
- Build classification models to predict churn
- Generate business recommendations for reducing churn

---

## 🔧 Tools & Skills Demonstrated

- **Data Cleaning & Processing** (`pandas`, `datetime`, `missing values`)
- **Churn Label Creation** (custom logic based on last purchase date)
- **Feature Engineering** (recency, frequency, payment totals, etc.)
- **Modeling** (`Logistic Regression`, `Random Forest`, `train/test split`)
- **Evaluation Metrics** (`accuracy`, `precision`, `recall`, `F1`, `confusion matrix`)
- **Data Visualization** (`matplotlib`, `seaborn`, heatmaps)

---

## 📊 Notebooks

| Notebook | Description |
|----------|-------------|
| `01_data_loading_cleaning.ipynb` | Load and clean raw datasets (orders, customers, payments, etc.) |
| `02_churn_labeling.ipynb` | Define churn (e.g., no activity in the last 6 months) and label customers |
| `03_feature_engineering.ipynb` | Build features per customer (e.g. #orders, avg payment, recency) |
| `04_modeling_churn.ipynb` | Train and evaluate classification models (Logistic Regression, Random Forest) |
| `05_results_visualization.ipynb` | Visualize performance results (confusion matrix comparison, metrics) |

---

## 🚀 How to Run the Project

To run this project locally:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/churn-prediction-olist.git
cd churn-prediction-olist

# (Optional) Create a virtual environment
conda create -n churn-env python=3.10
conda activate churn-env

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
