# Telco-Churn-Prediction
Predictive analytics project for customer churn using XGBoost and EDA

## Project Overview
This project analyses customer churn in a telecommunications company and builds a predictive model to identify customers at high risk of leaving. The goal is to provide actionable insights and strategies to improve customer retention and increase revenue.

**Key Highlights:**
- Exploratory Data Analysis (EDA) to understand churn drivers
- Data cleaning and feature engineering to prepare the dataset
- XGBoost classifier for churn prediction
- Model evaluation with classification metrics, confusion matrix, and ROC-AUC
- Postdictive analysis to identify where the model succeeds and fails
- Business recommendations for proactive customer retention

## Dataset
The dataset used is the `WA_Fn-UseC_-Telco-Customer-Churn` dataset. 
You can access it here: [Dataset Link](https://lnkd.in/erDSyNV7)

**Description:**
- Contains customer information, billing details, contract type, tenure, services subscribed, and churn status.
- **Target variable:** `Churn` (`0 = Stayed`, `1 = Left`)

**Important Features:**
- `tenure` – Customer duration with the company
- `monthlycharges` – Monthly payment amount
- `contract` – Type of subscription contract (`Month-to-Month`, `One Year`, `Two Year`)
- `internet_service` – Type of internet connection (`DSL`, `Fiber optic`, `None`)
