# Stroke-Prediction-
An intelligent medical decision-support tool that predicts the risk of stroke based on clinical and lifestyle data using a machine learning model trained on real-world healthcare data.

This project aims to assist healthcare professionals and patients in **early stroke risk assessment** using an interactive console-based input system and an accurate prediction engine built with Random Forest and SMOTE balancing.
## Overview

Stroke is one of the leading causes of death and disability worldwide. Predicting stroke early can help prevent severe outcomes and improve survival chances.

This project implements:
A machine learning pipeline that cleans data, handles class imbalance, and trains a model.
A real-time user interaction system that accepts **age, glucose level, hypertension**, and more.
Model evaluation using robust metrics: "Accuracy" and "AUC Score".
## Features

Real-world dataset from the healthcare domain
Data preprocessing and encoding of categorical variables
Class imbalance handled with "SMOTE (Synthetic Minority Over-sampling Technique)"
Uses "Random Forest Classifier" for high accuracy
Interactive console input system for real-time stroke risk prediction
Model evaluated with **Accuracy** and **AUC** on test data
##  Dataset

###Target variable: `stroke` (0 = no stroke, 1 = stroke)
####Features**:
`age`, `hypertension`, `heart_disease`, `avg_glucose_level`, `bmi`
 `gender`, `ever_married`, `work_type`, `Residence_type`, `smoking_status`
# Project Structure
stroke-prediction-ml/
│
├── healthcare-dataset-stroke-data.csv   # Source dataset
├── stroke_predictor.py                  # Main script: training + user input + prediction
├── requirements.txt                     # Dependencies
└── README.md                            # Project documentation


#Future Enhancements
 Deploy as a Streamlit web app for user-friendly access

 Build an Android app using Kivy or Flutter

 Deploy on cloud (Heroku, AWS, GCP)

 Add explainability using SHAP or LIME for model interpretation

 Compare multiple models and tune hyperparameters
