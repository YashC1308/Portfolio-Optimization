# Portfolio-Optimization


Description: This repository hosts a Python project aimed at optimizing investment portfolios using modern portfolio theory (MPT) techniques. The project utilizes financial data retrieval, data analysis, optimization algorithms, and visualization to construct an optimal investment portfolio based on a given set of assets.

Key Features:

Data Retrieval and Processing: Utilizes the Yahoo Finance API (yfinance) to fetch historical market data for a specified list of assets. The fetched data is then processed and organized into a DataFrame for further analysis.

Portfolio Metrics Calculation: Defines functions to calculate key portfolio performance metrics such as expected return, standard deviation (volatility), and Sharpe ratio. These metrics serve as crucial indicators for evaluating the risk-return trade-off of the portfolio.

Portfolio Optimization: Implements portfolio optimization using the scipy library's optimization module. The project seeks to find the optimal asset allocation that maximizes the Sharpe ratio, considering the user-defined risk-free rate and constraints on asset weights.

Analysis and Visualization: After optimization, the project provides insights into the optimal portfolio allocation, expected annual return, volatility, and Sharpe ratio. Additionally, it visualizes the optimal asset weights through a bar plot for easy interpretation
