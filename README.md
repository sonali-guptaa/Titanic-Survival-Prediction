# Titanic Survival Prediction
This repository contains a machine learning project aimed at predicting whether a passenger on the Titanic would have survived the sinking of the ship. The project explores various factors such as socio-economic status, age, gender, and other relevant features to determine their impact on survival rates.

## Project Overview
The Titanic disaster is one of the most infamous shipwrecks in history. On April 15, 1912, the Titanic sank after colliding with an iceberg, leading to the deaths of over 1500 passengers and crew. This project uses historical data from the Titanic voyage to build a classification system that predicts the likelihood of survival for individual passengers.

## Data Source
The dataset used in this project is the well-known Titanic dataset from Kaggle. 

## Methodology
- Data Cleaning: Handled missing values, data normalization, and feature engineering.
- Exploratory Data Analysis (EDA): Visualize the data to understand distributions and relationships between features.
- Feature Selection: Identified the most significant features that contribute to the prediction of survival.
- Model Building: Implemented various classification algorithms such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM).
- Model Evaluation: Compared the performance of different models using metrics like accuracy, precision, recall, and the F1 score.

## Results
The project identifies key factors that influence survival rates on the Titanic. Preliminary findings suggest that:
- Gender: Females had a significantly higher chance of survival.
- Class: Passengers in higher socio-economic classes (1st class) were more likely to survive.
- Age: Younger passengers had higher survival rates.
- Family Size: The number of relatives aboard had a varying impact on survival.

## How to Use
- Clone the repository
- Install required packages
- Run the Jupyter Notebook 'Titanic Classification task.ipynb' to follow the data analysis and model building process step-by-step.

## Acknowledgements
Kaggle for providing the Titanic dataset.
Open-source libraries such as Pandas, NumPy, Scikit-learn, and Matplotlib for making data analysis and machine learning accessible and efficient.
