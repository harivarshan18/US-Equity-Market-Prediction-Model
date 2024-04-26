# US Equity Market Prediction Model

## Project Overview

The US Equity Market Prediction Model is designed to analyze historical data of major tech stocks (Apple, Google, Microsoft, Amazon) and predict future trends based on their closing prices. Utilizing Python's powerful libraries, machine learning techniques, particularly Long Short-Term Memory (LSTM) networks, and advanced data analytics, this project aims to forecast stock prices to aid in investment decisions.

### Key Achievements

- **High Performance**: Developed a Python market prediction model with a 80.25% profitability rate, using GPU processing and parallelism.
- **Advanced Analytics**: Analyzed the coefficient of variation and feature distribution to find outliers and multicollinearity between trends.
- **Innovative Machine Learning**: Built an autoencoder (bottleneck classifier) for dimension reduction, generating an MLP via a Bayesian Optimizer.

### Features

- Fetches historical stock data using `yfinance`.
- Visualizes stock price trends and trading volumes.
- Computes moving averages and daily returns.
- Analyzes stock correlations and risks.
- Predicts future stock prices using LSTM neural networks.

## Getting Started

### Prerequisites

Ensure you have the following tools installed on your system:

- Python 3.8 or higher
- pip (Python package installer)

## Data Visualization

This model provides various visualizations to understand stock trends better:

- **Closing Price Graph**: Shows the historical closing prices of the stocks.
- **Volume Traded Graph**: Visualizes the trading volume over time.
- **Moving Averages**: Helps to see the trends over 10, 20, and 50 days.
- **Daily Returns**: Focus on the stock's daily fluctuation.
- **Correlation Heatmaps**: Analyzes the correlation between different stocks' returns and closing prices.

## Predictive Model

Using LSTM networks, the model predicts future stock prices based on patterns found in historical data. The process includes:

- Preprocessing and scaling data.
- Training LSTM on historical closing prices.
- Predicting future prices.
- Comparing predictions with actual data.

## Contributing

Feel free to fork the repository and submit pull requests. You can also open issues to discuss improvements or report bugs. We appreciate your input!

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

- Thanks to Yahoo Finance for providing the data.
- Inspired by various research papers on stock market prediction using LSTMs.

## Happy Trading! 📈
