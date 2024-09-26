# Stock Price Prediction Web App

This repository hosts a Flask web application that visualizes historical stock prices and predicts future trends using machine learning models. The data is sourced from Yahoo Finance, and the app offers visual insights and forecasting of stock price movements.

## Features

- **Flask Framework**: Serves as the backend of the application, handling requests and rendering the HTML templates.
- **Data Visualization**: Utilizes `matplotlib` for plotting stock price trends and predictions.
- **Stock Data**: Sourced directly from Yahoo Finance using the `pandas_datareader` library.
- **Machine Learning Models**:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - Ridge Regression
  - Polynomial Regression with a pipeline

## Dependencies

To run the application, you'll need the following Python libraries:

- Flask
- pandas
- numpy
- matplotlib
- mpld3
- pandas_datareader
- scikit-learn
- datetime

Install them with:

```bash
pip install -r requirements.txt
