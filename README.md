#Loan Default Prediction Project Documentation

##Project Overview
Did this project as a part of a fun AI study group I am part of.
This project is designed to predict loan default using a simple logistic regression model. The model is trained on a dataset containing features such as age, income, years, loan amount, and interest rate. The goal is to provide a quick and straightforward way to assess the likelihood of loan default based on user input.

##Dependencies
The project relies on the following Python libraries:

*pandas (version 1.3.3)*: For data manipulation and analysis.
*scikit-learn (version 0.24.2)*: For machine learning model training and prediction.
*StandardScaler from sklearn.preprocessing*: For standardizing the features.

These dependencies can be installed using the following command:

**pip install pandas scikit-learn==0.24.2**

How to Train the Model
1. Load the Dataset:
Ensure that you have a CSV file containing the loan data. In this example, the file is named loan_data_nov2023.csv.
2.Run the Training Script:
Open a Python environment and run the script. This script loads the dataset, trains a logistic regression model, and saves the trained model and scaler.
3. How to Make Predictions
Load the Trained Model.
Use the predict_loan_default function to make predictions based on user input. The function takes user input for age, income, years, loan amount, and interest rate, scales the input using the trained scaler, and predicts the likelihood of loan default as 0(not likely) or 1(likely).
