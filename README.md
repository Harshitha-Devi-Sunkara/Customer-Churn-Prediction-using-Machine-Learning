# Customer Churn Prediction using Machine Learning

## 📌 About This Project
In this project, I built a predictive model to identify potential customer churn using **Decision Trees, Random Forest, and XGBoost**. The goal was to analyze customer behavior and predict whether they would leave or stay.

To ensure data quality, I performed **data preprocessing**, including handling missing values, encoding categorical features, and balancing the dataset using **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance.

## 🏗 Model Training & Cross-Validation
- **XGBoost:** Implemented **manual cross-validation** using **Stratified K-Fold CV** to ensure balanced class distribution across folds.
- **Decision Tree & Random Forest:** Used **automatic cross-validation** (`cross_val_score`) for efficient evaluation.
- **5-Fold Cross-Validation** was used to ensure robustness.

## 🚀 Results
- **XGBoost & Random Forest achieved 84% cross-validation accuracy**.
- Evaluated model performance using **confusion matrix, classification report, and probability thresholds** to fine-tune decision-making.

## 🔧 Deployment & Predictions
- Deployed the model and enabled predictions on **new customer data**, achieving **78% confidence in No Churn cases**.
- The final model is saved as a **pickle file (`.pkl`)** for easy loading and real-time predictions.

## 📂 Repository Structure
- `notebooks/` → Jupyter Notebooks for exploration and modeling
- `models/` → Saved models (`.pkl`)
- `scripts/` → Python scripts for training and inference
- `README.md` → Project documentation

---
Feel free to check out the **code**, run the **notebooks**, or try the **model predictions** yourself! 🚀
