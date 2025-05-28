# 🪙 Bitcoin Price Prediction

This project predicts the **direction** (up/down) and the **closing price** of Bitcoin using machine learning models.

## 🔍 Models Used
- **Random Forest Classifier** – predicts if the price will go up or down
- **Random Forest Regressor** – predicts the actual closing price

## 📊 Features Used
- `open-close`: Difference between opening and closing prices
- `low-high`: Difference between lowest and highest prices
- `is_quarter_end`: Whether the current month is the end of a financial quarter

## 📁 Files
- `bitcoin_prediction.py`: Core script for training and prediction
- `bitcoin.csv`: Dataset (must be placed in the same folder)
- `requirements.txt`: Python dependencies

## ▶️ How to Run

1. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the main script:
   ```bash
   python bitcoin_prediction.py
   ```

## 📈 Output
- Classification Accuracy and Report
- Predicted price direction (📈 Up or 📉 Down)
- Estimated next-day Bitcoin closing price

## 🛠 Dependencies
See `requirements.txt`

---

**Note**: You must provide your own `bitcoin.csv` dataset or update the path to the dataset in the script.
