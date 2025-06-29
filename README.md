📈 Apple Stock Price Prediction using LSTM (2010–2023)
This project uses a Long Short-Term Memory (LSTM) deep learning model to predict Apple Inc. (AAPL) stock closing prices using historical data from 2010 to 2023.

📌 Project Overview
Predicts the next day’s stock closing price based on the past 60 days.
Uses only the Close price from Apple stock historical data.
Implements a deep learning model (LSTM) using TensorFlow/Keras.

🛠️ Technologies Used
Python
yfinance
pandas, numpy
matplotlib
scikit-learn (MinMaxScaler)
TensorFlow / Keras

📂 Data Source
Yahoo Finance via the yfinance Python library
Stock Symbol: AAPL
Date Range: 2010-01-01 to 2023-12-31

🔁 Workflow Summary
Data Collection
Downloaded historical AAPL data using yfinance
Preprocessing
Selected 'Close' prices
Scaled data using MinMaxScaler
Created 60-day time sequences
Model Building
Two-layer LSTM with Dropout and Dense output
Trained for 10 epochs, batch size 32
Prediction & Evaluation
RMSE: 6.53
Plotted actual vs predicted prices

📈 Results
The model accurately predicted stock trends with a Root Mean Squared Error (RMSE) of 5.41
Visualization shows predicted values follow actual stock movement closely

📊 Future Improvements
Use multiple features: Open, High, Low, Volume
Add technical indicators (e.g., Moving Averages, RSI)
Train for more epochs or use more complex models (e.g., GRU, Bi-LSTM)
Deploy as a web app or dashboard

🧠 Author
Afnan Ali Iqbal Ali
Location: Nagpur, India
Background: B.Com Graduate, Data Science Enthusiast

📎 License
This project is for educational purposes. Feel free to use or adapt it with proper credit.

