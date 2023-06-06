# Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict time series stock prices based on historical data. It utilises the Keras library with TensorFlow backend for implementing the LSTM model.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Installation

The following libraries are required:

- TensorFlow
- Keras
- Pandas
- NumPy
- Scikeras

To install these libraries, execute the following command:

```
pip install numpy pandas tensorflow keras scikeras
```
## Data

The stock price data should be in CSV format with the following columns:
- 'Date': The date of the stock price entry
- 'Open': The opening price of the stock
- 'High': The highest price of the stock during the day
- 'Low': The lowest price of the stock during the day
- 'Close': The closing price of the stock
- 'Volume': The trading volume of the stock
Ensure that the data file (AAPL.csv or your chosen file name) is placed in the directory.

## Usage

To use this project, follow these steps:

1. Clone this repository to your local environment including data file 'AAPL.csv'.
2. Install the required libraries using the command mentioned in the installation section.
3. Open the stock_price_prediction.ipynb notebook file using Jupyter Notebook or any compatible environment.
4. Modify the notebook to specify the data file name, model hyperparameters, and any other desired user configurations.
5. Run the notebook cells in sequential order to perform the following steps:
- Data loading and preprocessing
- LSTM model building
- Model training and validation
- Predictions and evaluation

## Conclusion

By implementing an LSTM model and training it on historical Apple stock price data, this project aims to provide accurate predictions of future stock prices. The predictive model can assist investors, financial analysts, and traders in making informed decisions about buying, selling, or holding Apple stock. The project showcases the potential of LSTM neural networks in predicting stock prices and demonstrates the importance of utilizing advanced machine learning techniques in financial forecasting.

## Contributing

Contributions are always welcome. If you have any suggestions, please feel free to create a pull request.