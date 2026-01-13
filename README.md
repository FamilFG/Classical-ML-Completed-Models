# Classical-ML-Completed-Models

A comprehensive collection of classical machine learning projects implementing various algorithms and techniques in Python. This repository contains practical examples of supervised learning, unsupervised learning, ensemble methods, and advanced ML techniques.

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Projects](#projects)
- [Setup Instructions](#setup-instructions)
- [Requirements](#requirements)

## Overview

This repository showcases implementations of popular machine learning algorithms with real-world datasets. Each project includes:
- Jupyter notebooks with detailed explanations
- Data preprocessing and feature engineering
- Model training and evaluation
- Visualizations and results

## Project Structure

```
├── Bagging/                              # Bagging ensemble methods
│   └── Random-Forest/                    # Random Forest classifier
├── Boosting/                             # Boosting ensemble methods (Gradient Descent, XGBoost)
├── Cancer-Prediction/                    # Binary classification - Cancer prediction
├── Customer-Churn-Prediction/            # Binary classification - Customer churn prediction
├── Decision-Trees/                       # Decision Tree implementations with hyperparameter tuning
│   ├── Basic-Grid-Randomized-Search/
│   └── Hyperparameter-Tuning/
├── Dron-Delivery-Code/                   # Regression - Delivery time prediction
├── E-Commerce-Sales-Prediction/          # Regression - Sales forecasting
├── IBM-Telco-Customer-Churn-Prediction/  # Binary classification - Churn prediction (IBM dataset)
├── K-Means/                              # Unsupervised learning - Clustering
├── Linear-Regression/                    # Linear regression implementations
├── Logistic-Regression/                  # Logistic regression implementations
├── BasicBankSystem.py                    # Basic banking system implementation
└── FirstEx.py                            # First exercise/example
```

## Projects

### Classification Projects

#### **Cancer-Prediction**
- Binary classification predicting cancer diagnosis
- Datasets: `Cancer_Data.csv`, `synthetic_cancer_full.csv`
- Notebooks: Cancer prediction and DataFrame creation examples

#### **Customer-Churn-Prediction**
- Predicting customer churn for business retention
- Multiple datasets: `churn.csv`, `customer-churn.csv`
- Practical business use case

#### **IBM-Telco-Customer-Churn-Prediction**
- IBM Telco dataset for churn prediction
- Classification with telecom customer data
- Datasets: `churn.csv`, `customer-churn.csv`

#### **Logistic-Regression**
- Multiple logistic regression examples
- Datasets: Exam scores, Framingham heart disease, Iris, Titanic survival, Online retail
- Binary and multi-class classification

### Regression Projects

#### **Linear-Regression**
- Multiple linear regression implementations
- Datasets: Boston Housing, Car Prediction, Online Retail, House prices
- Different scaling and preprocessing approaches

#### **E-Commerce-Sales-Prediction**
- Time series and regression analysis
- Sales forecasting for e-commerce businesses

#### **Dron-Delivery-Code**
- Delivery time prediction using regression
- Competition/Kaggle-style project

### Ensemble Methods

#### **Bagging**
- Random Forest classifier implementation
- Ensemble bagging techniques

#### **Boosting**
- **Gradient Descent Regressor**: GBM for regression
- **XGBoost Regressor**: Advanced boosting for various datasets
- Datasets: Heart disease, house prices, laptop prices

#### **Decision-Trees**
- Basic decision tree implementation
- Hyperparameter tuning with:
  - Optuna (Bayesian optimization)
  - Grid and Randomized Search
- Overfitting analysis and prevention

### Unsupervised Learning

#### **K-Means**
- Clustering implementation
- Unsupervised learning example

## Setup Instructions

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone or download this repository

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

Or install common ML packages:
```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn xgboost optuna catboost
```

4. Start Jupyter:
```bash
jupyter notebook
```

## Requirements

### Core Libraries
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **scikit-learn**: Machine learning algorithms and utilities
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **xgboost**: Extreme Gradient Boosting
- **optuna**: Hyperparameter optimization framework
- **catboost**: Gradient boosting on decision trees

### Standard Tools
- **jupyter**: Interactive notebooks
- **ipython**: Enhanced interactive Python

## Usage

1. Navigate to the project of interest
2. Open the `.ipynb` notebook file in Jupyter
3. Run cells sequentially to see model training and results
4. Modify datasets or parameters to experiment

## Notes

- Each project folder contains a README with specific instructions
- Datasets are included or linked within project folders
- Most notebooks are self-contained and can be run independently
- Results may vary slightly due to random seeds and data splits

## License

See LICENSE file for details.

---

**Last Updated**: January 2026  
**Author**: Data Science Projects Collection
