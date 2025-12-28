# Diabetes Prediction using Machine Learning
📌 Project Overview

This project focuses on building a supervised machine learning model to predict whether a person is diabetic or not based on medical diagnostic data. The goal is to demonstrate the complete end-to-end machine learning pipeline, from data preprocessing to model evaluation and real-world prediction.

🎯 Objective

To develop a binary classification model that predicts diabetes using medical attributes such as glucose level, BMI, blood pressure, and age.

📂 Dataset

The dataset contains medical information of patients.

Each record represents one patient.

The target variable is Outcome:

0 → Not Diabetic

1 → Diabetic

Features include:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

🧠 Machine Learning Approach

Type: Supervised Learning

Problem: Binary Classification

Model Used: Logistic Regression

🛠️ Technologies & Libraries

Python

NumPy – Numerical computations

Pandas – Data manipulation and analysis

Scikit-learn –

Data preprocessing

Model training

Model evaluation

🔄 Project Workflow

Import required libraries

Load and explore the dataset

Perform exploratory data analysis (EDA)

Separate features and target variable

Split data into training and testing sets

Apply feature scaling using StandardScaler

Train the Logistic Regression model

Evaluate the model using:

Accuracy Score

Confusion Matrix

Classification Report

Predict diabetes for a single new patient

📊 Model Evaluation

The model performance is evaluated using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-score

These metrics help assess how well the model predicts diabetic and non-diabetic cases.

🧪 Single Patient Prediction

The trained model can predict diabetes for new patient data by:

Scaling the input features

Passing them to the trained model

Interpreting the output in a human-readable form

This demonstrates real-world usability of the model.

📌 Conclusion

A machine learning model was successfully developed to predict diabetes using medical data. The project demonstrates how supervised learning techniques can assist in early disease detection and healthcare decision support.

🚀 How to Run the Project

Open the notebook in Google Colab or Jupyter Notebook

Upload the dataset file (.csv or .xls)

Run all cells from top to bottom

Observe the evaluation metrics and prediction results

📎 Internship Task

This project was completed as part of a Machine Learning Internship – Week 1 Task, focusing on practical implementation and understanding of core ML concepts.
