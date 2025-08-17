# Time Series Forecasting for Portfolio Management Optimization

## Project Overview

### Business Objective
Guide Me in Finance (GMF) Investments seeks to enhance portfolio management through advanced time series forecasting. By leveraging predictive models, GMF aims to optimize asset allocation, minimize risks, and improve investment outcomes for clients.

### Situational Overview (Business Need)
As a Financial Analyst at GMF, the objective is to apply time series forecasting techniques on historical financial data. This involves analyzing market trends, building predictive models, and recommending portfolio adjustments to maximize returns while managing associated risks.

### Data
The project utilizes historical financial data from three key assets:
- **Tesla (TSLA)**: High-growth stock.
- **Vanguard Total Bond Market ETF (BND)**: Provides stability.
- **S&P 500 ETF (SPY)**: Offers diversified market exposure.

Data will be sourced from YFinance for the period from **July 1, 2015, to July 31, 2025**, including metrics such as Open, High, Low, Close prices, and Volume.

### Expected Outcomes
Participants will acquire skills in:
- API usage for data extraction.
- Data wrangling and preprocessing.
- Time series modeling (ARIMA, LSTM).
- Portfolio optimization and visualization.
- Backtesting strategies for performance evaluation.

### Instructions
The project consists of five main tasks:

## Task 1: Preprocess and Explore the Data
1. **Data Extraction**: Use YFinance to extract historical data for TSLA, BND, and SPY.
2. **Data Cleaning**:
   - Check for missing values and handle them appropriately.
   - Normalize or scale data as required.
3. **Exploratory Data Analysis (EDA)**:
   - Visualize closing prices to identify trends.
   - Analyze daily percentage changes to observe volatility.
   - Perform outlier detection.
   - Conduct statistical tests to assess stationarity.

## Task 2: Develop Time Series Forecasting Models
1. **Model Implementation**:
   - Implement ARIMA/SARIMA for classical forecasting.
   - Construct an LSTM model for deep learning forecasting.
2. **Training and Testing**:
   - Split data chronologically into training and testing sets.
   - Compare model predictions against the test set.
3. **Parameter Optimization**:
   - Optimize ARIMA parameters using techniques like grid search.
   - Experiment with LSTM architecture and hyperparameters.
4. **Model Evaluation**:
   - Assess performance using metrics like MAE, RMSE, and MAPE.

## Task 3: Forecast Future Market Trends
1. **Generate Forecasts**:
   - Use the best-performing model to predict Tesla's stock prices for 6-12 months.
2. **Forecast Analysis**:
   - Visualize forecasts with historical data and confidence intervals.
   - Analyze trends, volatility, and potential market opportunities.

## Task 4: Optimize Portfolio Based on Forecast
1. **Expected Returns**:
   - Use the forecasted return for TSLA and historical returns for BND and SPY.
2. **Covariance Matrix**:
   - Compute the covariance matrix for asset returns.
3. **Efficient Frontier**:
   - Run optimization simulations to generate the Efficient Frontier.
   - Identify and mark key portfolios (Maximum Sharpe Ratio and Minimum Volatility).
4. **Portfolio Recommendation**:
   - Recommend an optimal portfolio with expected returns, volatility, and Sharpe Ratio.

## Task 5: Strategy Backtesting
1. **Define Backtesting Period**: Use the last year of data for backtesting.
2. **Benchmark Creation**: Establish a benchmark portfolio (e.g., static 60% SPY / 40% BND).
3. **Simulate Strategy**:
   - Hold the optimal portfolio for a set period, with possible rebalancing.
4. **Performance Analysis**:
   - Compare cumulative returns of the strategy against the benchmark.
   - Calculate final Sharpe Ratio and total return.

