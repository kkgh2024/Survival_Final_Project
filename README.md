
# Patient Survival Decision Support System

A machine learning–powered decision support application that predicts one-year patient survival probability based on demographic, clinical, and treatment-related factors.
The system is designed to support healthcare analytics use cases and demonstrate a production-ready ML workflow, from training to deployment.

## 🔍 Problem Statement

Healthcare providers often struggle to identify the factors that most strongly influence patient survival after treatment.
This project addresses that challenge by leveraging historical clinical data and machine learning to estimate survival likelihood and support data-driven decision-making.

## 🚀 Solution Overview

The solution consists of:

A Gradient Boosting classification model trained on patient data

A Streamlit web application for interactive prediction and visualization

A reproducible ML pipeline with saved model artifacts

## 🧠 Machine Learning Approach

Model: Gradient Boosting Classifier

Target: One-year survival (Survived_1_year)

#### Features:

Demographics (Age, BMI)

Lifestyle factors (Smoking status)

Clinical history (Previous conditions, mental condition)

Treatment type

#### Performance: ~83% accuracy after hyperparameter tuning

## 🛠️ Tech Stack

Python

Pandas / NumPy

Scikit-learn

Streamlit

Plotly

Joblib

## 📂 Project Structure


patient-survival-prediction-app/
│
├── app/
│   └── app.py                 # Streamlit application
│
├── data/
│   └── Survival.csv           # Sample / anonymized data
│
├── models/
│   ├── gradient_boosting.pkl  # Trained Gradient Boosting model
│   └── feature_names.pkl      # Saved feature schema for inference
│
├── train_model.py             # Model training & evaluation pipeline
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation




## ⚙️ How to Run Locally
#### 1. Install dependencies
pip install -r requirements.txt

#### 2. Train the model
python train_model.py

#### 3. Run the app
streamlit run app/app.py

## 📊 Application Features

Interactive patient data input

Real-time survival prediction

Probability-based risk scoring

Exploratory visualizations

Model performance evaluation (ROC, confusion matrix)

## 📌 Notes

The model and feature schema are persisted to ensure training–inference consistency

This project is for educational and demonstration purposes only

## 👤 Author
Khalida Khaldi

M.S. Data Science

Focus: Machine Learning, Analytics, Deployment

