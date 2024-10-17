# Diabetes Dataset - Linear Regression Model

This project applies a **Linear Regression** model on the **Pima Indians Diabetes Database** to predict diabetes outcomes (whether a person has diabetes) using health-related features. The project is implemented using **Python** and the **scikit-learn** library and evaluates the model using **K-Fold Cross Validation**. Performance metrics such as **Mean Squared Error (MSE)** and **R-squared (R²)** are used to assess the model's effectiveness.

## Project Overview

### Objective

The objective of this project is to develop a **predictive model** for identifying diabetes cases based on several health-related indicators. These indicators serve as the features for the model, and the model aims to predict whether a person has diabetes (binary outcome: 1 for diabetes, 0 for no diabetes).

### Features

The dataset contains the following features:

- **Pregnancies**: Number of times the person has been pregnant.
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-hour serum insulin (mu U/ml).
- **BMI**: Body Mass Index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: A function that scores likelihood of diabetes based on family history.
- **Age**: Age (years).

The target variable is **Outcome**, which is a binary variable (0 = no diabetes, 1 = diabetes).

## Project Setup

### Requirements

Ensure you have the following libraries installed to run the project:

```bash
pip install numpy pandas scikit-learn matplotlib
