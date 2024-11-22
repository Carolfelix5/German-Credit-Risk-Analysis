# German Credit Risk Analysis

This repository contains a machine learning project aimed at predicting credit risk for German financial data. The project involves building and evaluating models to classify credit risk as high or low, with a focus on accuracy and deployment readiness.

## Project Overview

The project includes:
- **Dataset**: Preprocessed German credit data with features such as `Gender`, `Age`, `EstimatedSalary`, and `Risk`.
- **Models Used**:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - Gradient Boosting Classifier
- **Best Model**: The Random Forest model achieved the highest cross-validation accuracy.
- **Deployment**: A GUI application was developed using Tkinter for easy interaction with the trained model.

## Features

- Exploratory Data Analysis (EDA) to understand feature impact on credit risk.
- Hyperparameter tuning and model evaluation using cross-validation.
- User-friendly GUI to predict credit risk based on input data.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `tkinter`
