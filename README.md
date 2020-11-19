![Banner](https://github.com/Hafizah/Life-Insurance-Premium-Random-Forest-Model/blob/main/2.png)

## Problem Statement

An insurance company wants to improve its cash flow forecasting by better predicting the annual life insurance premium using demographic and basic customer health risk 
metrics at the time of application.

## Objective

Build a machine learning model that can predict the premium for a life insurance based on customer's basic information.

## Dataset 
Variable | Description
---- | -------
**Age** | Age of applicant (primary beneficiary)
**Sex** | Gender of applicant (female, male)
**BMI** | An applicant’s weight in kilograms divided by the square of height in meters
**Children** | Number of children or dependents
**Smoker** | Smoking habits
**Region** | Northeast, Southeast, Southwest, Northwest
**Charges** | Life insurance premium based on the data given (target variable)

## Methodology
- Performed exploratory data analysis
- Used feature selection 
- Built accurate model
- Designed frontend of webpage with Streamlit
- Deploy model on Heroku

## Result 
Random Forest Regression model with accuracy of 85.4%

## What you need to deploy
File | Description
---- | ------
Procfile | State what commands are to be run on start up
requirements.txt | Python package dependencies needed on Heroku
scaler_value.pkl | Saved data preparation objects
setup.sh | Set up the platform project directory
Life_Insurance_Model.pkl | Serialized model 
streamlitpredictinsurancecharges.py | Frontend codes

## Web App front page visual
![Front page](https://github.com/Hafizah/Life-Insurance-Premium-Random-Forest-Model/blob/main/App%20front%20page.png)

## Conclusion

A simple random forest regression model can be used to create a machine learning model that can then be deployed for business purposes.
