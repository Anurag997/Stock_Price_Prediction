# Stock_Price_Prediction

## Overview

This project involves building a stock price prediction model using Long Short-Term Memory (LSTM) neural networks. The goal is to predict the stock prices of Amazon using historical data. LSTM is a type of recurrent neural network (RNN) well-suited for time series data like stock prices.

## Dataset

The dataset used for this project was downloaded from Kaggle:

- Dataset: [Amazon Stock Price (All Time)](https://www.kaggle.com/datasets/kannan1314/amazon-stock-price-all-time/code?datasetId=1619941)

The dataset includes historical stock price data for Amazon, including features like Date, Open, High, Low, Close, Adjusted Close, and Volume.

## Project Structure

- `Stock_Prediction.ipynb`: Jupyter Notebook containing the code for the stock price prediction using LSTM.
- `Amazon_Stock.csv`: The dataset file in CSV format.

## How to Use

1. Clone the repository to your local machine using:
git clone https://github.com/your-username/stock-prediction-lstm.git

2. Open the Jupyter Notebook file `Price_Prediction.ipynb` using Jupyter Notebook or Jupyter Lab.

3. Install the required Python packages, if not already installed, using:
pip install pandas numpy matplotlib tensorflow scikit-learn

4. Run each cell of the notebook sequentially to train the LSTM model and make predictions on the test data.

5. The notebook provides visualizations and graphs showing the actual and predicted stock prices.

## Dependencies

- Python 3.x
- Pandas
- Numpy
- Matplotlib
- TensorFlow
- Scikit-Learn

## Acknowledgements

- Dataset Source: [Amazon Stock Price (All Time)](https://www.kaggle.com/datasets/kannan1314/amazon-stock-price-all-time/code?datasetId=1619941)

