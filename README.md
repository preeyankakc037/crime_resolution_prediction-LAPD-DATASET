# 🔎 Crime Case Resolution Prediction (Machine Learning)

Predicting whether reported crime cases will be **resolved** or remain **under investigation** using real-world law enforcement data.

---

## 📌 Project Definition

This project develops a supervised machine learning framework to predict crime case resolution outcomes using historical administrative crime records. The objective is to model whether a reported case will be resolved or remain ongoing, while identifying the most influential operational and contextual factors affecting investigative outcomes.

---

## 📖 Project Description

Using the *Crime Data from 2020 to Present* dataset provided by the Los Angeles Police Department (LAPD) via the Los Angeles Open Data Portal, this project implements a complete end-to-end ML pipeline.

### 🔬 Methodology Overview

- Exploratory Data Analysis (EDA)
- Data cleaning and structured preprocessing
- Feature engineering (temporal, spatial clustering, contextual encoding)
- Baseline and advanced model development
- Class imbalance handling experiments
- Bayesian hyperparameter optimization
- SHAP-based interpretability analysis

### 🤖 Models Implemented

- Logistic Regression (Baseline)
- Random Forest
- XGBoost
- **LightGBM (Best Performing Model)**

### 📊 Performance Highlights

- **Best Model:** LightGBM  
- **Primary Metric:** ROC-AUC ≈ 0.86  
- Tree-based boosting models consistently outperformed linear models  
- Contextual crime attributes were stronger predictors than temporal variables  

For full experimental design, evaluation details, limitations, and ethical considerations, please refer to the complete academic report included in this repository.

---

## 📂 Repository Structure

- `EDA_and_Preprocessing.ipynb` – Data exploration and feature engineering  
- `Model_Training.ipynb` – Model development and evaluation  
- `Final_Report.pdf` – Detailed academic documentation  

---

## 🌟 What Makes This Project Stand Out?

- Interpretability-first approach using SHAP
- Real-world large-scale administrative crime dataset (~1M records)
- Careful leakage control and validation strategy
- Algorithm-level optimization outperforming resampling methods
- Research-grade documentation with limitations and future directions

This project focuses not only on predictive performance, but also on actionable insight and responsible ML application in high-stakes public safety contexts.

---

## 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![SHAP](https://img.shields.io/badge/SHAP-Model%20Explainability-yellow)
![ROC-AUC](https://img.shields.io/badge/Metric-ROC--AUC-brightgreen)
![Project Type](https://img.shields.io/badge/Type-Academic%20Research-success)

---

## 📌 Summary

This repository demonstrates how structured crime data can be transformed into predictive insight using modern machine learning techniques. With optimized LightGBM achieving strong ROC-AUC performance and SHAP ensuring transparency, the project balances performance, interpretability, and methodological rigor.

For complete technical depth, refer to the accompanying report.

---

**Author:** Priyanka Khatri  
**Program:** BSc Computer Science with AI  
