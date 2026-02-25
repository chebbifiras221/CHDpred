# 🫀 Coronary Heart Disease (CHD) Prediction using PySpark

> Scalable Machine Learning model to predict 10-year Coronary Heart
> Disease (CHD) risk using the Framingham Heart Study dataset.

------------------------------------------------------------------------

## 📌 Project Overview

Coronary Heart Disease (CHD) remains one of the leading causes of
mortality worldwide. Early identification of individuals at high risk
enables preventive interventions and improved clinical outcomes.

This project implements a binary classification pipeline using PySpark
to predict whether a patient is likely to develop CHD within 10 years,
based on clinical and behavioral features.

------------------------------------------------------------------------

## 🎯 Objectives

-   Build a predictive model for 10-year CHD risk
-   Apply scalable data preprocessing with PySpark
-   Perform feature engineering and normalization
-   Train and evaluate a Logistic Regression classifier
-   Analyze model performance using classification metrics

------------------------------------------------------------------------

## 🛠 Technology Stack

-   Python
-   PySpark (MLlib)
-   Logistic Regression
-   Matplotlib
-   Seaborn
-   Framingham Heart Study Dataset (Kaggle)

------------------------------------------------------------------------

## 📂 Dataset Description

Target Variable:

TenYearCHD - 0 → No CHD within 10 years\
- 1 → CHD within 10 years

Selected Features: - age - Sex_male - cigsPerDay - totChol - sysBP -
glucose

------------------------------------------------------------------------

## 🔬 Methodology

### 1️⃣ Data Preprocessing

-   Dropped irrelevant column: education
-   Renamed male → Sex_male
-   Cast numeric columns to DoubleType
-   Removed rows containing NULL values

### 2️⃣ Feature Engineering

-   Combined features using VectorAssembler
-   Standardized features using StandardScaler

### 3️⃣ Model Training

-   Train/Test split: 70% / 30%
-   Model: Logistic Regression
-   Input: Scaled feature vector

------------------------------------------------------------------------

## 📊 Results

### ✅ Accuracy

Accuracy: 85%

### 📉 Confusion Matrix

             Predicted 0   Predicted 1
  ---------- ------------- -------------
  Actual 0   921           11
  Actual 1   149           10

### 📈 Performance Metrics

-   Precision: 0.80\
-   Recall: 0.85\
-   F1-Score: 0.80

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Apply class balancing techniques
-   Compare with Random Forest and Gradient Boosting
-   Perform hyperparameter tuning
-   Deploy as API or dashboard

------------------------------------------------------------------------

## 📽 Project Presentation

Add your presentation PDF inside the repository and link it like this:

[View Project
Presentation](./Coronary_Heart_Disease_CHD_Prediction_PySpark.pdf)

------------------------------------------------------------------------

## 👤 Author

Firas Chebbi\
Machine Learning & Data Science
