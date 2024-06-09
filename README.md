# Introduction

## 1.1 Problem Description
Cardiovascular diseases (CVD) are one of the leading causes of death globally. Early assessment and prediction of cardio health risks can significantly reduce the mortality rate by enabling timely interventions. This project aims to build a predictive model to assess cardio health risk using a dataset from Kaggle.

## 1.2 Data Description
The dataset used in this project is the Cardio Health Risk Assessment dataset from Kaggle. It contains 270 observations and 14 features, including demographic information, medical test results, and diagnosis of heart disease presence or absence.

### Features:
- **Age**: Age of the patient
- **Sex**: Gender of the patient (0 = Female, 1 = Male)
- **Chest pain type**: Type of chest pain (1-4)
- **BP**: Blood Pressure in mmHg
- **Cholesterol**: Serum Cholesterol in mg/dl
- **FBS over 120**: Fasting Blood Sugar > 120 mg/dl (0 = No, 1 = Yes)
- **EKG results**: Results of electrocardiogram (0-2)
- **Max HR**: Maximum Heart Rate achieved
- **Exercise angina**: Exercise induced angina (0 = No, 1 = Yes)
- **ST depression**: ST depression induced by exercise relative to rest
- **Slope of ST**: Slope of the peak exercise ST segment (1-3)
- **Number of vessels fluro**: Number of major vessels colored by fluoroscopy (0-3)
- **Thallium**: Thallium stress test result (3-7)
- **Heart Disease**: Presence (1) or Absence (0) of heart disease

## 1.3 Objective
The primary objective of this project is to develop a deep learning model to predict the presence of heart disease based on the provided features. We will explore various neural network architectures, perform hyperparameter optimization, and evaluate the model's performance using standard metrics.
