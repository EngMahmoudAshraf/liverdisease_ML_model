# Liver Disease Prediction using Machine Learning

This project applies machine learning techniques to classify whether a person is likely to have liver disease based on clinical features. It is based on a publicly available dataset containing patient records.

## 📌 Project Overview

Liver disease can be detected early using clinical and biochemical features. In this notebook, we build and evaluate various classifiers to distinguish between healthy individuals and those with liver disease.

The pipeline includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling and selection
- Training and comparing multiple machine learning models
- Evaluating model performance

## 📂 Dataset

The dataset used is the *Indian Liver Patient Dataset (ILPD)* available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29). It includes:
- Age
- Gender
- Total and direct bilirubin
- Enzyme levels (ALT, AST, ALP)
- Proteins (Total and Albumin)
- Albumin and Globulin ratio
- Target label: Liver Disease (1) or No Disease (2)

## 🤖 Models Used

The following machine learning models were evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 📊 Evaluation Metrics

Each model was evaluated using:
- Accuracy
- Confusion Matrix
- Classifica