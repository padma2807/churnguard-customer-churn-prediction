# ChurnGuard - Customer Churn Prediction

## Project Overview

ChurnGuard is a machine learning project that predicts whether a customer is likely to churn.

The project uses customer service and billing information and applies data cleaning, preprocessing, and Logistic Regression.

## Tasks Completed

### Task 1 - Data Exploration
- Loaded the customer churn dataset
- Checked dataset shape
- Identified missing values
- Checked duplicate rows
- Examined inconsistent categorical values

### Task 2 - Data Cleaning
- Removed duplicate rows
- Removed unnecessary customer ID
- Standardised categorical values
- Converted TotalCharges to numeric
- Removed invalid tenure values
- Removed invalid MonthlyCharges values
- Filled missing values

### Task 3 - Classification Model
- Encoded the target variable
- Applied one-hot encoding to categorical features
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Evaluated the model using accuracy and classification report

### Task 4 - Prediction Script
- Retrained Logistic Regression on the full cleaned dataset
- Created an interactive prediction script
- Allows users to enter customer information
- Predicts whether the customer is likely to CHURN or STAY

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Google Colab
- GitHub

## Model

The classification model used in this project is:

Logistic Regression

## Example Prediction

Input:

- Tenure: 24 months
- Monthly Charges: 65.50
- Total Charges: 1500
- Senior Citizen: No
- Contract: Month-to-month

Output:

Prediction: This customer is likely to STAY.
