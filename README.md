# PHOS-PREDECT-AI: Integrated Prediction of Price and Quantity in the Phosphate Industry
## Project Overview
PHOS-PREDECT-AI is a machine learning-based solution designed to predict phosphate industry trends, focusing on the price and quantity of phosphate. Using datasets related to the phosphate sector and leveraging the power of Random Forest Regression, this project aims to provide insights into market behaviors, aiding decision-making for stakeholders.



## Introduction
This project was developed in collaboration with the Office Chérifien des Phosphates (OCP), focusing on improving decision-making in the phosphate industry through data science and machine learning techniques. The primary goal is to predict market-related variables, such as phosphate prices and production quantities, by analyzing historical data.

## Problem Statement
The phosphate industry faces various challenges, including price fluctuations and varying production levels. Accurately predicting these factors can help companies like OCP to optimize production and maintain competitive advantage in the global market.

## Dataset
### Price Prediction Dataset
The dataset used for price prediction contains various features influencing the global phosphate price. Key variables include market trends, production levels, and demand forecasts.

### Phosphate Quantity Dataset
This dataset includes information about phosphate production and export volumes, allowing for predictions on future production quantities based on historical data.

## Data Preprocessing
### Data Cleaning
The data was cleaned by identifying and handling missing values, standardizing text fields, and ensuring consistency across datasets.

### Data Transformation
Once cleaned, the data was transformed for model input, involving feature scaling and splitting the dataset into training and testing sets.

## Model Implementation
Random Forest Regression
A Random Forest Regression model was implemented in Python using the scikit-learn library to predict the price and quantity of phosphate. This method was chosen for its high accuracy and robustness in handling complex datasets.

## Model Evaluation
The model was evaluated using R² scores and other performance metrics, showing promising results in predicting phosphate industry trends.

## Frontend Design
### User Interface
The project's user interface was designed using Bootstrap for responsive design, with custom CSS for aesthetic improvements. It features:

Home page for dataset selection
Prediction forms for entering model inputs
Results page displaying predictions with an option to download detailed reports
### Backend Setup
The backend was developed using Flask, handling data storage, model execution, and report generation through ReportLab.

## Results
The model successfully predicts phosphate prices and production quantities, with a user-friendly interface for data input and result visualization.

## Conclusion
PHOS-PREDECT-AI provides a robust and scalable solution for predicting market behaviors in the phosphate industry, offering valuable insights for stakeholders to make informed decisions.
