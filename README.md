# 🧠 Parkinson’s Disease Prediction Using Machine Learning

This project focuses on predicting Parkinson’s Disease using Machine Learning models based on biomedical voice measurements.
The goal is to assist in early detection of Parkinson’s Disease by analyzing patterns in patient data.

## 📌 Project Overview

Parkinson’s Disease is a progressive neurological disorder that affects movement and speech.
Early diagnosis is critical but challenging.

In this project, we:

Use machine learning algorithms to classify patients

Analyze voice-related biomedical features

Predict whether a person has Parkinson’s Disease or not

## 🎯 Objectives

Preprocess and analyze Parkinson’s dataset

Train ML models for disease prediction

Evaluate model performance using accuracy and metrics

Build a reliable prediction system

## 🛠️ Technologies Used

Python

Jupyter Notebook

Libraries

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

## 📂 Project Structure
parkinson-disease-prediction/
│
├── parkinson_disease.ipynb   # Main Jupyter Notebook
├── README.md                 # Project documentation
└── dataset.csv               # Parkinson’s dataset (if included)

## 📊 Dataset Description

The dataset consists of biomedical voice measurements of patients.

Key Features:

MDVP:Fo(Hz)

MDVP:Fhi(Hz)

MDVP:Flo(Hz)

Jitter (%)

Shimmer

HNR

RPDE

DFA

PPE

Target Variable:

status

1 → Parkinson’s Disease

0 → Healthy

🔍 Methodology

Data Loading

Exploratory Data Analysis (EDA)

Data Preprocessing

Handling missing values

Feature scaling

Train-Test Split

Model Training

Logistic Regression

Support Vector Machine (SVM)

Random Forest (if used)

Model Evaluation

Accuracy score

Confusion matrix

Classification report

## 🚀 How to Run the Project
✅ Prerequisites

Make sure you have Python installed (3.8+ recommended).

Install required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn

▶️ Run the Notebook
jupyter notebook


Open:

parkinson_disease.ipynb


Run all cells sequentially.

## 📈 Results

The trained machine learning model achieves high accuracy in predicting Parkinson’s Disease.

SVM generally performs best for this dataset.

The model can effectively distinguish between healthy individuals and Parkinson’s patients.

🧪 Sample Prediction

The model can take patient feature values as input and predict:

Parkinson’s Disease detected

No Parkinson’s Disease detected

## ⚠️ Disclaimer

This project is for educational purposes only.
It should not be used as a medical diagnostic tool without professional validation.

## 📌 Future Enhancements

Use deep learning models

Deploy using Flask / Streamlit

Add real-time voice input

Improve dataset size and diversity

## 👩‍💻 Author

Mohammed Ansar Abrar Hussain
Machine Learning Project – Parkinson’s Disease Prediction

## 📜 License

This project is open for academic and learning purposes.
