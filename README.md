**Overview:**
This project focuses on the forecasting of JP Morgan's stock prices using advanced time series analysis techniques and machine learning models. The models include:
ARIMA for statistical trend analysis,
LSTM for capturing sequential patterns in stock prices,
XGBoost for handling non-linear relationships and complex interactions,
A Hybrid ARIMA-LSTM model for enhanced predictive performance.
The project aims to evaluate the strenghts and weakness of each model and provide accurate stock price predictions while analyzing the impact of historical market events.

**Dataset:**
The dataset used for this project is JP Morgan's historical stock data (2004–2024), which includes:
Open, High, Low, Close prices
Adjusted Close prices
Trading volume
Source
The dataset was sourced from publicly available financial platforms (e.g., Yahoo Finance).
Dataset Link: JPMorgan Chase & Co. (JPM) stock historical prices and data – Yahoo Finance 

**Methodology**:
The forecasting pipeline was divided into the following steps:

Exploratory Data Analysis (EDA)
Objective: Understand the dataset, identify trends, and detect anomalies or patterns.
Key Tasks:
Analyzed historical price movements (Open, Close, High, Low, Volume).
Examined correlations between features.
Performed volatility analysis using a 30-day rolling standard deviation.

**Model Implementation**:
Four models were implemented to predict stock prices:

**ARIMA:** Captures linear trends and seasonal components.
Trained using historical price data with differencing to ensure stationarity.

**LSTM:** A deep learning model for sequential data.
Designed with multiple layers and tuned for hyperparameters such as epochs, learning rate, and sequence length.

**XGBoost:** A gradient boosting model for non-linear relationships.
Utilized time series features like lagged prices and rolling averages for feature engineering.

**Hybrid ARIMA-LSTM:** Combines ARIMA's statistical precision with LSTM's ability to capture non-linear dependencies.
ARIMA extracts linear trends, and LSTM learns residual patterns.

**Performance Metrics**
Each model was evaluated using:
Mean Absolute Error (MAE),
Mean Squared Error (MSE),
R-squared (R²) Score

**Visualization:**
Actual vs. Predicted prices for each model were plotted.
Future predictions were displayed with confidence intervals to show uncertainty.

**Conclusion**:
This project demonstrates the strengths and limitations of statistical and machine learning approaches for stock price forecasting:
Hybrid ARIMA-LSTM: The most effective model, combining linear and non-linear forecasting capabilities.

 
