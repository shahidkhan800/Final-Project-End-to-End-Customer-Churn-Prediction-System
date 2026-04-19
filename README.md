# Final-Project-End-to-End-Customer-Churn-Prediction-System
Predict whether a customer will churn (leave a service) based on historical customer data.  

# End-to-End Customer Churn Prediction System

## Project Overview
This project predicts whether a customer will churn (leave a service) based on their past data. Customer churn is a major problem for telecom companies, and predicting it helps businesses save money by offering targeted discounts to unhappy customers.

## What I Did
In this project, I built a complete machine learning pipeline. My steps included:
1. **Data Cleaning:** Handled missing values in the 'TotalCharges' column.
2. **Data Preprocessing:** Changed text data (like "Yes" and "No") into numbers using Label Encoding, and scaled the numbers so the computer could understand them evenly.
3. **Model Training:** Trained two different machine learning models to classify customers as "Stay" or "Leave".
4. **Evaluation:** Tested the models on hidden data to see how accurate they were.

## Tools Used
* **Python:** The main programming language.
* **Pandas & Matplotlib:** Used for opening the data table and drawing visual graphs.
* **Scikit-Learn:** Used for training the Logistic Regression and K-Nearest Neighbors algorithms.

## The Results
After testing the models, here is how they performed on the test data:

| Model | Accuracy | F1-Score |
| :--- | :--- | :--- |
| Logistic Regression | 79% | 0.55 |
| K-Nearest Neighbors | 74% | 0.51 |

**Conclusion:** The Logistic Regression model performed slightly better at correctly predicting which customers would leave. 

## How to Run This Code
1. Download the `WA_Fn-UseC_-Telco-Customer-Churn.csv` dataset from Kaggle.
2. Upload the dataset to Google Colab.
3. Run the complete Python script to see the data cleaning and model predictions.
