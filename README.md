# Stock Price Dataset 

Introduction
Welcome to the Stock Price Dataset Overview! This dataset contains historical stock price data for four companies: Amazon (AMZN), Domino's Pizza (DPZ), Bitcoin (BTC), and Netflix (NFLX). The dataset includes daily stock prices from May 1, 2013, to May 14, 2019.

Dataset Details

The dataset comprises the following columns:
- Date: The date of the stock price record.
- AMZN: Stock price of Amazon on the given date.
- DPZ: Stock price of Domino's Pizza on the given date.
- BTC: Stock price of Bitcoin on the given date.
- NFLX: Stock price of Netflix on the given date.
Purpose
The purpose of this dataset is to provide historical stock price data for analysis and research purposes. Analysts, investors, and researchers can use this dataset to study trends, patterns, and relationships in stock prices over time.

Potential Analysis
Potential analyses that can be conducted using this dataset include:

1.Correlation analysis to explore relationships between the stock prices of different companies.

2.Time series analysis to forecast future stock prices based on historical data.

3.Volatility analysis to measure the risk associated with each stock.



The Stock Price Dataset provides valuable historical data that can be used for a wide range of analyses in the financial domain. Researchers and analysts can leverage this dataset to gain insights into the behavior of stock prices and make informed decisions in the stock market.


markdown
Copy code
# Stock Price Prediction using LSTM

## Introduction

Welcome to the Stock Price Prediction using LSTM repository! In this project, we leverage the power of Long Short-Term Memory (LSTM) neural networks to predict stock prices. LSTM networks are well-suited for time series data like stock prices due to their ability to capture long-term dependencies.

## Dataset Overview

The dataset used in this project contains historical stock price data for multiple companies, including Amazon (AMZN), Domino's Pizza (DPZ), Bitcoin (BTC), and Netflix (NFLX). Each row in the dataset represents the stock prices for a specific date.

## Model Building

### LSTM Model Architecture
# Define the LSTM model

model = Sequential()

model.add(LSTM(50, return_sequences=True, input_shape=(X_train.shape[1], 1)))

model.add(LSTM(50, return_sequences=True))

model.add(LSTM(50))

model.add(Dense(1))

model.compile(loss='mean_squared_error', optimizer='adam')

# Model Evaluation

## Mean Squared Error (MSE)

The Mean Squared Error is a commonly used metric to evaluate regression models' performance. It calculates the average of the squared differences between the actual values and the predicted values. A lower MSE indicates better model performance.
To evaluate the LSTM model's performance on the test set, we calculated the Mean Squared Error using the predicted stock prices  and the actual stock prices.

# Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.


# Contact

📧 Email: thangamani1128@gmail.com

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.






