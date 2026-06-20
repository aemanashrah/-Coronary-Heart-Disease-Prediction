🫀 Coronary Heart Disease (CHD) 10-Year Risk Prediction
A Machine Learning project predicting the 10-year risk of Coronary Heart Disease using Logistic Regression.
📌 Overview
This repository contains an end-to-end data analytics and machine learning pipeline designed to predict whether a patient is at risk of developing Coronary Heart Disease (CHD) within the next 10 years. By leveraging patient demographic, behavioral, and clinical metrics, this project provides actionable predictive insights that simulate a preliminary medical screening tool.
🛠️ Tech Stack & Environment
Environment: Python (Jupyter Notebook)
Data Manipulation: Pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-Learn (Logistic Regression, StandardScaler, Classification Metrics)
📊 Dataset
The project utilizes the Framingham Heart Study dataset (framingham.csv), encompassing various patient risk factors:
Demographics: Age, Sex
Behavioral: Current smoking status, Cigarettes per day
Medical History: BP medication usage, Prevalent stroke, Prevalent hypertension, Diabetes
Biometrics: Total cholesterol, Systolic/Diastolic BP, BMI, Heart rate, Glucose levels
⚙️ Methodology
Data Preprocessing: Handled missing records (NaN removal), dropped statistically irrelevant features, and normalized continuous numerical metrics using StandardScaler to prevent data leakage and ensure uniform scaling.
Exploratory Data Analysis (EDA): Analyzed target class distributions, visualized key health risk factors, and mapped feature interactions using correlation heatmaps.
Model Training: Built a binary classification model using Logistic Regression, utilizing Log Loss (Binary Cross-Entropy) to cleanly separate the risk categories.
Evaluation: Assessed model robustness using Accuracy, Classification Reports (Precision/Recall/F1), Confusion Matrices, and ROC-AUC curves.
📈 Results
Overall Accuracy: 83.39%
ROC-AUC Score: 0.72
The model demonstrates strong predictive capability, effectively distinguishing between high-risk and low-risk patient profiles and serving as a reliable baseline for medical data classification.

<img width="715" height="578" alt="Screenshot 2026-06-17 185551" src="https://github.com/user-attachments/assets/a846f145-0efe-4da0-9aa5-081f99ab8ced" />
