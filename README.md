
# BEL Stock Price Forecasting

This project aims to forecast the stock prices of **Bharat Electronics Limited (BEL)** using three time series forecasting methods: **ARIMA**, **SARIMA**, and **LSTM**. It includes data collection, model building, evaluation, and visualization using Python and Power BI.

## 📂 Files

- `main.py`: The main script that performs the following:
  - Downloads BEL stock price data using `yfinance`
  - Splits the data into training and testing sets
  - Forecasts stock prices using ARIMA, SARIMA, and LSTM models
  - Evaluates each model with RMSE
  - Plots actual vs forecasted prices

- `stock_data.csv`: Original BEL stock price data downloaded via yFinance.

- `forecast_output_cleaned.csv`: Cleaned forecast results for each model, suitable for reporting or visualization.

- `Time series.pbix`: Power BI report with time series charts and forecast comparison for BEL stock prices.

## 📊 Models Used

### 1. ARIMA
- Captures linear trends and seasonality in the data
- RMSE is computed to evaluate performance

### 2. SARIMA
- A seasonal extension of ARIMA to model periodic patterns

### 3. LSTM (Long Short-Term Memory)
- Deep learning model capable of learning from long-term dependencies in time series data

## 🧪 Evaluation

Each model's Root Mean Squared Error (RMSE) is computed and used to compare their accuracy.

```bash
ARIMA RMSE: <value>
SARIMA RMSE: <value>
LSTM RMSE: <value>
```

*(These values are printed in `main.py` when executed.)*

## 📈 Visualization

- Python: Forecast comparison plot showing actual and predicted prices for all models.
- Power BI: Interactive time series report for further analysis and stakeholder presentations.

## ⚙️ Requirements

- Python 3.7+
- pandas
- numpy
- yfinance
- matplotlib
- statsmodels
- scikit-learn
- tensorflow
- google.colab (if running in Colab)

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 🚀 Running the Project

To run the script:

```bash
python main.py
```

If you're using Google Colab, make sure to adjust any file download or display settings accordingly.

## 📌 Author

- Developed by Sarthak
- For research/academic/internship purposes

## 📄 License

This project is licensed under the MIT License.
