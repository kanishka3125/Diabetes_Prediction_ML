# Diabetes Prediction using Machine Learning
## 📌 Project Overview

This project focuses on building a supervised machine learning model to predict whether a person is diabetic or not based on medical diagnostic data. The goal is to demonstrate the complete end-to-end machine learning pipeline, from data preprocessing to model evaluation and real-world prediction.

## 🎯 Objective

To develop a binary classification model that predicts diabetes using medical attributes such as glucose level, BMI, blood pressure, and age.

## 📂 Dataset

1. The dataset contains medical information of patients.

2. Each record represents one patient.

3. The target variable is Outcome:

    ```0``` → Not Diabetic

    ```1``` → Diabetic

## Features include:

1. Pregnancies
2. Glucose
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI
7. Diabetes Pedigree Function
8. Age

## 🧠 Machine Learning Approach

1. Type: Supervised Learning

2. Problem: Binary Classification

3. Model Used: Logistic Regression

## 🛠️ Technologies & Libraries

1. Python
2. NumPy – Numerical computations
3. Pandas – Data manipulation and analysis
4. Scikit-learn –
   - Data preprocessing
   - Model training
   - Model evaluation

## 🔄 Project Workflow

1. Import required libraries
2. Load and explore the dataset
3. Perform exploratory data analysis (EDA)
4. Separate features and target variable
5. Split data into training and testing sets
6. Apply feature scaling using StandardScaler
7. Train the Logistic Regression model
8. Evaluate the model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

9. Predict diabetes for a single new patient

## 📊 Model Evaluation

The model performance is evaluated using:

1. Accuracy Score
2. Confusion Matrix
3. Precision, Recall, and F1-score

These metrics help assess how well the model predicts diabetic and non-diabetic cases.

## 🧪 Single Patient Prediction

The trained model can predict diabetes for new patient data by:

1. Scaling the input features
2. Passing them to the trained model
3. Interpreting the output in a human-readable form

This demonstrates real-world usability of the model.

## 📌 Conclusion

A machine learning model was successfully developed to predict diabetes using medical data. The project demonstrates how supervised learning techniques can assist in early disease detection and healthcare decision support.

## 🚀 How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the dataset file (```.csv``` or ```.xls```)
3. Run all cells from top to bottom
4. Observe the evaluation metrics and prediction results

## 📎 Internship Task

This project was completed as part of a Machine Learning Internship – Week 1 Task, focusing on practical implementation and understanding of core ML concepts.
