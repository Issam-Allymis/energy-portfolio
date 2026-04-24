# Energy Consumption Forecasting (Time Series + Machine Learning)

## Project Overview
This project analysis historical energy consumptiondata to identify temporal patterns and build a predictive model for energy demand using time-based features.
The goal is to understand how energy usage changes over time and to build a simple machine learning model to predict demand.

---

## Objectives
- Analyse energy consumption patterns over time
- Identify seasonal and daily trends in usage
- Engineer time-based features
- Build a regression model to predict energy demand
- Evaluate model performance using error metrics

---

## Dataset
The dataset contains hourly energy consumption data including:
- Datetime
- Energy usage (MW)

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Scikit-Learn
- Google Colab

---

## Feature Engineering
From the datetime column, the following features were created:
- Hour of day
- Day of week
- Month of year

These features were used as predictors for energy consumption.

---

## Machine Learning Model
A Linear Regression model was used as a baseline predictive model.

### Train/Test Split
The dataset was split chronologically:
- Training set: historical data
- Test set: future unseen data

---

## Model Evaluation
- Mean Absolute Error (MAE): ~ calculated value
- Root Mean Squared Error (RMSE): ~67 MW

---

## Key Findings
- Energy consumption follows strong daily patterns, peaking in the eveing (6-7pm)
- Higher demand is observed during summer months
- The model captures general trends but struggles with peak fluctuations and nuances.

---

## Business Insight 
Energy demand is highly dependent on time-based patterns. Understanding these trends can help optimise energy distribution and improve planning for peak demand periods.

---

## Conclusion
This project demonstrates a full machine learning pipeline including data preprocessing, feature engineering, model training and evaluation. While a simple linear model was used, it provides a strong baseline for future improvements using more complex algorithms.

---

## Future Improvements
- Include weather data as additional features
- Test non-linear models (Random Forest, Gradient Boosting)
- Improve feature engineering with lag variables

---

## Author
Issam

