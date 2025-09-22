# Predicting Potential Donors for CharityML

A machine learning project to identify individuals likely to donate to charity based on census data.

![Machine Learning](https://img.shields.io/badge/Machine-Learning-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.2+-orange)

## 📊 Project Overview

This project aims to help CharityML identify potential donors by predicting individuals with income >$50,000 using the 1994 U.S. Census data. The model achieves **85.87% accuracy** in classifying potential donors.

**Key Highlights:**
- ✅ **85.87% Accuracy** after hyperparameter optimization
- ✅ **Comparative analysis** of multiple ML algorithms
- ✅ **Feature importance analysis** for actionable insights
- ✅ **End-to-end ML pipeline** from data cleaning to deployment-ready model



## 🏆 Results Summary

| Model | Accuracy | F-Score | Status |
|-------|----------|---------|---------|
| Random Forest (Optimized) | **85.87%** | **0.7296** | 🏆 **Best Model** |
| Random Forest (Base) | 84.23% | 0.6813 | |
| SVM | 84.23% | 0.6851 | |
| Logistic Regression | 84.17% | 0.6826 | |

## 📁 Project Structure
finding_donors/
│
├── data/
│ └── census.csv # Original dataset

├── notebooks/
│ └── finding_donors.ipynb # Main Jupyter notebook

├── visuals.py # Visualization utilities

├── requirements.txt # Dependencies

└── README.md # This file

## 📈 Methodology
1. Data Preprocessing
Handling skewed features: Log transformation for capital-gain and capital-loss

Normalization: MinMax scaling for numerical features

Encoding: One-hot encoding for categorical variables

Train-Test Split: 80-20 split with stratification

2. Model Comparison
Evaluated multiple algorithms:

Random Forest Classifier

Support Vector Machines (SVM)

Logistic Regression

