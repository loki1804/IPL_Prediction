# First Innings Score Prediction - IPL

## Overview
This project aims to predict the first innings score in IPL matches using machine learning techniques. The dataset includes past IPL matches with key features like batting team, bowling team, overs, runs, wickets, and more.

## Dataset
The dataset used in this project contains ball-by-ball details of IPL matches. Important features include:
- Batting team
- Bowling team
- Overs
- Runs scored
- Wickets fallen
- Previous match performances

## Data Preprocessing
Key preprocessing steps include:
- Removing unnecessary columns (e.g., batsman, bowler, venue)
- Filtering out inconsistent teams
- Removing data from the first 5 overs to ensure stability
- Converting date column to datetime format

## Feature Engineering
Features such as current run rate (CRR) and last 5-over performance are engineered to improve model accuracy.

## Model Training
The project involves training a regression model using:
- **Linear Regression**
- **Decision Tree Regression**
- **Random Forest Regression**
- **XGBoost Regression**

## Results
The model performance is evaluated using metrics like:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Installation & Usage
### Prerequisites
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost

## Conclusion
This project provides a predictive model for estimating IPL first innings scores. Future improvements could include deep learning models or additional match conditions.

## Contributors
- G.LOHITH KUMAR

