# Loan Approval Prediction - Kaggle Competition (Playground Series S4E10)

## 📌 Overview
This repository contains my solution for the **Loan Approval Prediction** competition from the Kaggle Playground Series - Season 4, Episode 10. The goal of this competition was to predict whether an applicant is approved for a loan using machine learning techniques.

- **Competition Link:** [Loan Approval Prediction - Kaggle](https://kaggle.com/competitions/playground-series-s4e10)
- **Ranking:** #867  
- **Best Score:** **0.96518 (ROC AUC Score)**  

## 📊 Dataset
The dataset used in this competition was synthetically generated from real-world financial data. It includes various applicant details such as credit history, income, loan amount, and other features relevant to loan approval.

- **Train Dataset:** Used to train the machine learning models.
- **Test Dataset:** Used for final predictions.
- **Target Variable:** `loan_status` (1 = Approved, 0 = Not Approved)

## 🛠️ Approach & Solution
### 1. **Exploratory Data Analysis (EDA)**
   - Checked for missing values and handled them appropriately.
   - Performed statistical analysis and visualizations (histograms, box plots, correlation matrix).

### 2. **Feature Engineering**
   - Created new features based on domain knowledge.
   - Encoded categorical variables using one-hot encoding and label encoding.
   - Scaled numerical features using StandardScaler.

### 3. **Model Selection & Training**
   - Used `XGBoost` as the primary model due to its robustness in handling tabular data.
   - Tuned hyperparameters using **Optuna** for optimal performance.
   - Handled outliers using box plots to improve generalization.

### 4. **Evaluation & Submission**
   - The model was evaluated using **ROC AUC Score**.
   - Best submission achieved a **score of 0.96518**.

## 🚀 How to Use
### 1. Clone the repository
```bash
git clone https://github.com/madhukar6143/Kaggle-Loan-Approval-Prediction.git
cd Kaggle-Loan-Approval-Prediction
