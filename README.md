# Customer-Churn-Analysis
Predictive Modelling using Decision Trees and ANNs
# Customer Churn & Total Charges Prediction

This project implements a dual-model approach to analyze telecommunications customer data. The primary objective is to predict **Total Charges**—a key financial metric—using both traditional machine learning and deep learning architectures.

## 🚀 Project Overview
The analysis follows a structured pipeline:
1. [cite_start]**Data Inspection:** Initial analysis of a 7000+ record dataset including tenure, contract types, and monthly charges.
2. [cite_start]**Preprocessing:** Specialized handling of `totalCharges` (conversion from object to numeric) and implementation of One-Hot Encoding and Standard Scaling to prevent data leakage.
3. **Regression Analysis:** - **Decision Tree Regressor:** Used for baseline predictive modeling.
   - [cite_start]**Artificial Neural Network (ANN):** A multi-layer deep learning model built with Keras/TensorFlow to capture non-linear patterns.

## 📊 Key Results
- Successfully handled missing data (NaN) through post-split imputation.
- Achieved predictive results visualized through "Actual vs. Predicted" scatter plots for the ANN regression model.
- [cite_start]Established a robust 80/20 train-test split for model validation.

## 🛠️ Installation & Usage
To replicate this environment, clone the repository and install the dependencies:

```bash
pip install -r requirements.txt
