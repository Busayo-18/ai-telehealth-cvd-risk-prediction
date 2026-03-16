# ai-telehealth-cvd-risk-prediction
An AI-powered telehealth system for early hypertension and cardiovascular disease risk screening using machine learning . Designed to improve early detection and healthcare accessibility in Africa.
# AI-Telehealth: CVD Risk Prediction (Group 9)

## 🩺 Project Overview
This project focuses on predicting hypertension and cardiovascular risk within the African context. We developed a machine learning pipeline that analyzes patient demographics, lifestyle factors (stress, income, education), and medical vitals to provide early risk assessment.

## 🚀 Key Features
- **Data Cleaning & Engineering:** Handled categorical encoding and introduced realistic lifestyle features (Stress Level, Sleep Patterns).
- **Model Shootout:** Compared Random Forest, Logistic Regression, and SVM to find the most accurate predictor.
- **Robustness:** Introduced 10% noise to simulate real-world diagnostic uncertainty, achieving a realistic **90.15% accuracy**.
- **Deployment Ready:** Exported the winning model as a `.pkl` file for integration into telehealth platforms.

## 📊 Technical Results
- **Final Model:** Random Forest (Winning Algorithm)
- **Accuracy:** 90.15%
- **Key Predictors:** Age, Stress Levels, and BMI.

## 🛠️ Installation
```bash
pip install -r requirements.txt