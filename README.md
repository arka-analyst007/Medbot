# Medbot
Project Title: Medical Insurance Premium Prediction System
Objective: Developed an end-to-end Machine Learning solution to predict medical insurance premiums based on individual health and demographic factors, streamlining the inquiry process for insurance providers.

Key Features & Implementation:
Predictive Modeling: Built a regression model using the Random Forest Regressor algorithm to estimate insurance costs based on features such as age, BMI, gender, smoking status, region, and number of children.

Data Analysis & Preprocessing: * Performed Exploratory Data Analysis (EDA) using Seaborn and Matplotlib to understand data distribution and feature correlations.
Executed data cleaning and feature engineering, including the conversion of categorical variables (Gender, Smoker, Region) into numerical formats for model compatibility.

Model Performance: Achieved an R-squared (R2) score of 80%, indicating high predictive accuracy by optimizing model parameters such as n_estimators and max_depth.
Web Application: Deployed the model as an interactive web application using Streamlit, allowing users to input their data via sliders and dropdowns to receive real-time premium estimates.

Technical Stack:
Languages: Python.
Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Pickle.
Deployment: Streamlit.

Impact: The system automates the manual inquiry process, making premium estimation more efficient and providing immediate insights into how factors like smoking or age significantly impact insurance costs.
