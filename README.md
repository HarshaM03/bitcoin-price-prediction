# Bitcoin Price Prediction

This project predicts the **direction** (up/down) and the **closing price** of Bitcoin using machine learning models.

## Models Used
- **Random Forest Classifier** – predicts if the price will go up or down
- **Random Forest Regressor** – predicts the actual closing price

## Features Used
- `open-close`: Difference between opening and closing prices
- `low-high`: Difference between lowest and highest prices
- `is_quarter_end`: Whether the current month is the end of a financial quarter

## Files
- `bitcoin_prediction.py`: Core script for training and prediction
- `bitcoin.csv`: Dataset (must be placed in the same folder)
- `requirements.txt`: Python dependencies


