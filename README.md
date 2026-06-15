# Adversarial Robustness Evaluation of Machine Learning-Based Phishing URL Detectors with Explainability Analysis Using SHAP

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## 📌 Overview
This repository contains the code, datasets, and methodology implementation for the research paper titled **"Adversarial Robustness Evaluation of Machine Learning-Based Phishing URL Detectors with Explainability Analysis Using SHAP"**. 

The study focuses on evaluating how resilient tree-based ensemble models (such as XGBoost and LightGBM) are against adversarial attacks designed to bypass phishing URL detection systems. Furthermore, it employs SHapley Additive exPlanations (SHAP) to provide an in-depth explainability analysis, revealing how these models make decisions and how adversarial perturbations manipulate those decisions.

## 🎯 Research Objectives
* **Robustness Evaluation:** To test ML-based phishing detectors against various adversarial attack scenarios.
* **Explainability:** To interpret the feature importance and model decision-making process before and after attacks using SHAP.
* **Comparative Analysis:** To compare the performance and resilience of different models under adversarial settings.

## 🛠️ Methodology & Tech Stack
* **Machine Learning Models:** XGBoost, LightGBM, [Tambahkan model lain jika ada, misal: Random Forest]
* **Explainable AI (XAI):** SHAP (SHapley Additive exPlanations)
* **Programming Language:** Python
* **Key Libraries:** `scikit-learn`, `xgboost`, `lightgbm`, `shap`, `pandas`, `numpy`

## 📂 Repository Structure
```text
├── data/                   # Dataset files (original and adversarial)
├── notebooks/              # Jupyter notebooks for EDA and SHAP visualization
├── src/                    # Source code for model training and evaluation
│   ├── adversarial_phising.ipynb
│   
│  
│   
├── results/                # Output graphs, SHAP summary plots, and metrics
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
