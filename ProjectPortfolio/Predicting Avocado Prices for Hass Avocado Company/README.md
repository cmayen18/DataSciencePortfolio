
# Project Title: Predicting Avocado Prices for Hass Avocado Company's Expansion

## Overview:
The project aimed to assist Hass Avocado Company in its expansion endeavors by developing a predictive model for forecasting the average price of Hass avocados in the US market. The dataset comprised weekly retail scan data from April 2015 to March 2018, encompassing various attributes such as average price, volume, type (conventional/organic), and region. Leveraging Python and a multitude of libraries including statmodels, pmdarima, fbprophet, and scikit-learn, the project followed a comprehensive approach encompassing data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Objective:
The primary objective was to build and assess a robust predictive model to forecast the average price of Hass avocados, enabling Hass Avocado Company to make informed decisions regarding the expansion of avocado farms in different regions. The project sought to leverage historical sales data to anticipate future price trends accurately.

## Tools:
- Language: Python
- Libraries: statmodels, pmdarima, fbprophet, scikit-learn
- Dataset: Provided by retailers' cash registers, containing weekly retail scan data of Hass avocados in the US market.

## Implementation:
1. **Data Preprocessing**: Handling missing values, label encoding, one-hot encoding.
2. **Exploratory Data Analysis**: Identifying trends and seasonal patterns in the data.
3. **Feature Engineering**: Creating new relevant features from existing data.
4. **Model Building**:
   - Linear Regression
   - Random Forest Regressor
   - XGB Regressor
   - Facebook Prophet
   - ARIMA
   - SARIMAX
5. **Model Evaluation**: Utilizing metrics like R-squared, MAPE, MAE, and visual inspection of forecast vs. actual values.

## Key Learnings:
- Understanding the importance of data preprocessing and feature engineering in improving model performance.
- Familiarity with various time series forecasting techniques such as ARIMA, SARIMAX, and Facebook Prophet.
- Evaluation of models using appropriate metrics to ensure model reliability.
- Importance of modular code organization for scalability and maintainability of the project.

