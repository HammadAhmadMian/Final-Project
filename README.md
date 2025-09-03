Gold Price Forecasting with LSTM This project develops and evaluates a
deep learning model to predict future gold prices using Long Short-Term
Memory (LSTM) networks. It leverages extensive feature engineering with
technical indicators to enhance prediction accuracy and includes a
Bayesian LSTM for uncertainty quantification.

📊 Key Results The standard LSTM model achieved excellent performance on
the test set:

R² Score: 0.9818

Mean Absolute Error (MAE): \$30.74

Mean Absolute Percentage Error (MAPE): 1.46%

🛠️ Features & Engineering The model uses a rich set of engineered
features:

Technical Indicators: RSI, Simple & Exponential Moving Averages (SMA,
EMA), Fibonacci Retracement Levels.

Statistical Features: Rolling volatility, lag features.

Temporal Features: One-hot encoded day of the week.

🧠 Models Standard LSTM: A 2-layer LSTM network for deterministic point
forecasting.

Bayesian LSTM: A probabilistic model that provides prediction intervals
and quantifies uncertainty.

📁 Project Structure text ├── Gold_Price_Forecasting_LSTM.ipynb \# Main
Jupyter Notebook with full code └── README.md \# This file 🚀 How to Run
Install Requirements:

bash pip install torch pyro-ppl yfinance mplfinance scikit-learn
matplotlib pandas numpy tqdm Run the Notebook: Open and run all cells in
Gold_Price_Forecasting_LSTM.ipynb. The code handles data downloading,
preprocessing, model training, and evaluation.

📜 Citation This work was submitted in partial fulfilment of the MSc in
Data Science at the University of Hertfordshire.

Name: Hammad Ahmad SRN: 23072948

🔗 Data Source All financial data is sourced from Yahoo Finance using
the yfinance Python library for research purposes.
