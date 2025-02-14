# Inflation Rate Prediction in US

This study will focus on analysis of inflation rate in the US during 2002-2022 to understand how macroeconomic factors affect to the inflation in the US.

The data visualisation using some package such as matplot, seaborn, and plotly, will be use to visually analyse the relationship between inflation rate and macroeconomic features. This will provide insight details for making business and monetary policy decisions.

An ARIMA model has been selected for the machine learning approach.

---
## Feature definition

- UNRATE(%) = Unemployment Rate of US for particular month
- CONSUMER CONF INDEX = Consumer Confidence Index provided by Conference Board
- PPI-CONST MAT = Producers Purchase Index- Construction Materials
- CPIALLITEMS = Consumer Price Index- All Items for the US
- INFLATION(%) = Inflation rate in the US
- MORTGAGE INT. MONTHLY AVG(%) = Average Mortgage interest rate of all Weeks of a particular month
- MED HOUSEHOLD INCOME = Median Household Income in the US
- CORP. BOND YIELD(%)
- MONTHLY HOME SUPPLY
- % SHARE OF WORKING POPULATION = Share of Population between the age 18 and 60
- GDP PER CAPITA
- QUARTERLY REAL GDP
- QUARTERLY GDP GROWTH RATE (%)
- CSUSHPISA = S&P/Case-Shiller U.S. National Home Price Index given by FRED
---
## Features

1. Data preprocessing and visualization
2. Time series analysis of inflation data
3. ARIMA model training and optimization
4. Forecasting future inflation rates
5. Performance evaluation and visualization
---
## Data source
Dataset link: https://www.kaggle.com/datasets/sagarvarandekar/macroeconomic-factors-affecting-us-housing-prices/data

---
## Installation

To run this project locally, follow these steps:

### Prerequisites
Ensure you have Python installed along with the following libraries:
pip install pandas numpy matplotlib statsmodels

### Clone the Repository
git clone https://github.com/your-username/us-inflation-arima.git
cd us-inflation-arima

### Usage
python main.py

---

## Model Development

1. Data Collection & Preprocessing: Load and clean historical inflation data.
2. Exploratory Data Analysis (EDA): Visualize trends and check stationarity.
3. Model Selection: Use ACF/PACF plots to determine ARIMA parameters.
4. Model Training & Tuning: Fit the ARIMA model and optimize parameters.
5. Forecasting: Predict future inflation rates and evaluate performance.

---
## Results
1. Visual representation of past and predicted inflation rates.
2. Model evaluation metrics, achieving R² = 0.973, MAE = 0.249, MSE = 0.112, and RMSE = 0.335.




