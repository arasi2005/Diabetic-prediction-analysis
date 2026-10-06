# Diabetic-prediction-analysis
  #Diabetes Prediction Web App

A machine learning project that predicts whether a person is likely to have diabetes from medical details. It includes a Flask web app and stores every prediction in a SQLite database.

> Learning project only. It is not medical advice.

## Features
- Data cleaning and feature scaling
- Logistic Regression model trained with scikit-learn
- Flask web app with a prediction API that returns the result and risk percentage
- Input validation for missing or invalid values
- Every prediction saved to SQLite

## Tech Stack
Python, pandas, NumPy, scikit-learn, Flask, SQLite, HTML/JavaScript

## Dataset
Pima Indians Diabetes dataset (768 rows, 8 input columns). The target column is Outcome (1 = diabetes, 0 = no diabetes). Zeros in Glucose, BloodPressure, SkinThickness, Insulin and BMI are invalid, so they were treated as missing and replaced with the column median.

## Model Result
- Model: Logistic Regression (80/20 train-test split)
- Accuracy: XX% (replace with the value printed by train_model.py)

## Project Structure
```
diabetes-prediction/
  app.py
  train_model.py
  diabetes.csv
  model.pkl
  scaler.pkl
  requirements.txt
  templates/index.html
```

## How to Run
```
pip install -r requirements.txt
python train_model.py
python app.py
```
Open http://127.0.0.1:5000 in your browser.

## Author
Punnagaiarasi A - github.com/arasi2005
