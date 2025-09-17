**Heart Disease Risk Prediction Using Machine Learning**

This repository contains the code, methodology, and findings from my MSc dissertation:
"Analysing the Risk of Heart Disease Associated with Co-morbidities Using Machine Learning and Prediction" (University of Wolverhampton, June 2025).

**📖 Project Overview**

Cardiovascular diseases (CVDs) remain the leading cause of global mortality. This project explores the use of machine learning (ML) and explainable AI (XAI) to predict the risk of heart disease based on comorbidities and lifestyle factors.

Using the CDC’s BRFSS 2015 dataset, the project develops and evaluates multiple ML models, applying advanced preprocessing, feature selection, and interpretability methods to improve prediction and clinical trust.

**📊 Dataset**

Source: CDC BRFSS 2015 (via Kaggle)

Size: 70,692 survey responses, 22 variables

Features include: demographics, lifestyle habits, comorbidities (diabetes, hypertension, cholesterol), and self-reported health indicators.

**⚙️ Methodology**

**Data Preprocessing**

Imputation for missing values

Outlier handling (IQR method)

Class imbalance corrected using SMOTE

Feature scaling (Min-Max & Z-score normalization)

Categorical encoding (One-Hot / Label Encoding)

**Feature Selection**

Mutual Information (MI)

Cross-validation with recursive feature elimination and tree-based importance

**Machine Learning Models**

Logistic Regression (LR)

Random Forest (RF)

XGBoost (XGB)

Support Vector Machine (SVM)

k-Nearest Neighbors (KNN)

Naive Bayes (NB)

Multilayer Perceptron (MLP)

Deep Neural Network (DNN)

Stacked Ensemble Learning (RF, SVM, XGB + LR meta-learner)

TabNet (Deep learning for tabular data)

**Evaluation Metrics**

Accuracy, Precision, Recall, F1-score, ROC-AUC

10-fold Cross-validation

External validation using Cleveland Heart Disease dataset

**Interpretability**

SHAP (Shapley Additive Explanations) used for global and local feature importance.

**✅ Results**

**Best Model**: XGBoost

**Accuracy**: 91%

**ROC-AUC**: 0.965

**F1-Score**: 0.91

**Key Predictors**: Age, Income, General Health, Education, High Blood Pressure, High Cholesterol, Diabetes, Sex (Male).

**Insights**:

Socioeconomic factors (income, education) are as important as clinical variables.

SHAP explanations aligned with established clinical evidence.

**🔍 Key Findings**

**XGBoost outperformed all other models** in predictive accuracy and generalization.

**Explainable AI (SHAP)** increased model trust and provided interpretable feature contributions.

Social determinants of health (income, education) play a critical role in CVD risk.

Ensemble and deep learning methods show strong potential for **real-world clinical integration.**
