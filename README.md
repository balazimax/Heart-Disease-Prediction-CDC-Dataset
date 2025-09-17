**Heart Disease Risk Prediction Using Machine Learning**

This repository contains the code, methodology, and findings from my MSc dissertation:
"Analysing the Risk of Heart Disease Associated with Co-morbidities Using Machine Learning and Prediction" .

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


**RESULTS**

<img width="522" height="245" alt="image" src="https://github.com/user-attachments/assets/1c03427d-3aef-4ac7-b4d9-a9e2e0a1d15d" />

<img width="659" height="955" alt="image" src="https://github.com/user-attachments/assets/a4e20c47-64fe-4111-835d-02e6f1d0f00b" />

<img width="679" height="638" alt="image" src="https://github.com/user-attachments/assets/a5dc9725-9612-4c00-b8af-f9bf9772e132" />

<img width="528" height="501" alt="image" src="https://github.com/user-attachments/assets/2b02ccf1-eaab-4df8-a145-3d4406830558" />

<img width="604" height="275" alt="image" src="https://github.com/user-attachments/assets/ba233714-7972-4c76-adac-385c1b645172" />

<img width="529" height="228" alt="image" src="https://github.com/user-attachments/assets/ce0cca2c-ceb2-481a-945a-416b9ef0fd36" />

<img width="960" height="402" alt="image" src="https://github.com/user-attachments/assets/c8292ac2-d226-467d-a98a-3ba06f2f2da2" />

<img width="933" height="669" alt="image" src="https://github.com/user-attachments/assets/d3798c2a-9f53-4448-b11d-5ce533709e81" />

<img width="745" height="697" alt="image" src="https://github.com/user-attachments/assets/b96a8705-5431-4c01-a5ba-45b4e2fd2a15" />

<img width="645" height="561" alt="image" src="https://github.com/user-attachments/assets/ddc4a116-ac29-456b-8fa9-0cead71fa021" />

<img width="943" height="569" alt="image" src="https://github.com/user-attachments/assets/15091b59-7d1f-4aec-ac87-df912f0aa04b" />

<img width="814" height="336" alt="image" src="https://github.com/user-attachments/assets/24bc35b9-a7db-465f-947b-f0ceb8fcf6ff" />

<img width="922" height="582" alt="image" src="https://github.com/user-attachments/assets/ba16b713-379c-4bc8-9974-982e8cc3d5ab" />

<img width="781" height="528" alt="image" src="https://github.com/user-attachments/assets/bbe6f1dc-f103-47d2-a049-4343f4aa81f1" />

<img width="864" height="711" alt="image" src="https://github.com/user-attachments/assets/ea3285a2-0e09-4fdd-873f-033adf38710f" />

<img width="737" height="414" alt="image" src="https://github.com/user-attachments/assets/f7198797-094f-4680-b7ef-262df2578fc1" />

<img width="555" height="500" alt="image" src="https://github.com/user-attachments/assets/2ed0f121-d7fd-409b-af44-f3fc37355bcc" />

<img width="924" height="197" alt="image" src="https://github.com/user-attachments/assets/c8d2b044-7f58-4c0d-b1a8-e35908610236" />

<img width="805" height="464" alt="image" src="https://github.com/user-attachments/assets/d7299fd2-b806-4eda-868c-276a1c827621" />

<img width="944" height="544" alt="image" src="https://github.com/user-attachments/assets/ca898ab5-dc76-4ac4-be25-f171ca8f9ad3" />

<img width="433" height="655" alt="image" src="https://github.com/user-attachments/assets/9a75cdee-8f60-4cd9-801f-09c502b93a6c" />

<img width="408" height="334" alt="image" src="https://github.com/user-attachments/assets/3c5ef8ba-d2f1-4541-92e1-d41b69a7564e" />

<img width="398" height="334" alt="image" src="https://github.com/user-attachments/assets/443e51d7-72d6-4c3e-8c7e-3b4ebc5f2a2c" />

<img width="473" height="326" alt="image" src="https://github.com/user-attachments/assets/3b92b09c-789a-46b9-b498-2b33c3fd7d4d" />

<img width="454" height="308" alt="image" src="https://github.com/user-attachments/assets/71236cd7-750d-4550-9b04-476790b66238" />


