Obesity Level Prediction — Healthcare Data Science Exercise
📘 Project Overview

This repository contains a personal project in healthcare data science, aimed at practicing machine learning techniques to predict obesity levels based on lifestyle, dietary habits, and physical activity. This project is educational; the models are not clinically validated.

🧮 Dataset

Source: Mendoza Palechor & De la Hoz Manotas, 2019, Data in Brief
Dataset link

Samples: 2,111 individuals

Features: 17 attributes including physical activity, eating habits, and daily routines

Target: NObesity (7 classes: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III)

Data composition: 23% real data, 77% synthetic (via SMOTE)

Missing values: None

⚙️ Methodology

Data preprocessing (encoding, scaling)

Feature selection/engineering

Model training and evaluation using:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

XGBoost

LightGBM

SVM (RBF)

K-Nearest Neighbors

Metrics: Accuracy, Precision, Recall, F1-score, Macro AUC

📊 Results

Best model: LightGBM

Macro AUC: 0.99

Recall: 0.95

F1-score: 0.96

⚠️ Results are illustrative due to the synthetic nature of the dataset and intended for learning purposes only.

🧠 Key Learnings

End-to-end ML workflow for tabular healthcare data

Handling partially synthetic datasets

Model evaluation and comparison in multi-class classification

🔮 Future Work

Model interpretability using SHAP

Prototype interactive dashboard with Streamlit

Apply workflow to other datasets for further practice

🧰 Requirements

pandas
numpy
scikit-learn
xgboost
lightgbm
matplotlib
seaborn

