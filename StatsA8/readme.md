# Decision Tree Classification – Pima Indians Diabetes Dataset

## Project Overview

This project implements a Decision Tree Classifier using the Pima Indians Diabetes Dataset to predict whether a patient has diabetes based on medical and physiological information.

The practical focuses on understanding decision tree classification, evaluating model performance, and studying the concepts of Entropy, Information Gain, and Gini Index.

The classifier is trained using both Entropy and Gini criteria, and their performance is compared using accuracy and other evaluation metrics.

## Aim

To implement a Decision Tree Classifier using the Pima Indians Diabetes Dataset and understand the working of decision trees using Entropy, Information Gain, and Gini Index.

## Dataset

The Pima Indians Diabetes Dataset contains medical information about patients and their diabetes outcomes.

- **Total records:** 768
- **Total columns:** 9
- **Independent variables:** 8
- **Target variable:** Outcome

The dataset was uploaded and loaded into Google Colab using Pandas.

### Features

The dataset contains the following independent variables:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

The target variable is:

- **Outcome:** 0 indicates No Diabetes, and 1 indicates Diabetes.

## Libraries Used

- **Pandas** – For data loading and manipulation.
- **NumPy** – For numerical calculations.
- **Matplotlib** – For plotting graphs and visualizing the decision tree.
- **Scikit-learn** – For model training, testing, and evaluation.

## Steps Performed

### 1. Data Loading and Exploration

- Loaded the diabetes dataset using Pandas.
- Displayed the first five records.
- Checked the shape, column names, and data types.
- Checked for missing values.

The dataset contains 768 records and 9 columns.

### 2. Feature and Target Separation

The independent
