⛽ Time Series Forecasting of Monthly Oil Production
This project focuses on forecasting monthly oil production using both classical statistical models and advanced deep learning techniques. By analyzing historical data, it aims to capture underlying patterns, seasonality, and trends to deliver accurate long-term forecasts.

📊 Project Overview
Using real-world monthly oil production data, this project applies a combination of traditional time series models and modern neural network architectures. The goal is to compare performance, understand the strengths of each approach, and demonstrate the benefits of integrating statistical and deep learning models for effective forecasting.

🛠 Tech Stack

Programming Language: Python

Libraries: Pandas, Matplotlib, Statsmodels, Scikit-learn, TensorFlow/Keras

Models Implemented:

📈 AR (Auto Regressive)

📉 MA (Moving Average)

⚙️ ARMA (AutoRegressive Moving Average)

🔁 ARIMA (AutoRegressive Integrated Moving Average)

🌀 SARIMA (Seasonal ARIMA)

🧠 RNN (Recurrent Neural Network)

🧠 LSTM (Long Short-Term Memory)

🧠 GRU (Gated Recurrent Unit)

🔍 Features & Techniques

Time series decomposition: trend, seasonality, and noise extraction

Log transformation and differencing for stationarity

Residual diagnostics and visualization for model validation

Comparison using MAPE (Mean Absolute Percentage Error) for forecasting accuracy

Model selection using AIC (Akaike Information Criterion)

Long-term forecasting with deep learning architectures

📈 Results Summary
🔢 MAPE (Mean Absolute Percentage Error)
| Model   | Type          | MAPE (%) |
|---------|---------------|----------|
| AR      | Statistical   | 18.25%   |
| MA      | Statistical   | 18.71%   |
| RNN     | Deep Learning | 4.39%    |
| GRU     | Deep Learning | 4.31%    |
| LSTM    | Deep Learning | 3.58%    |

AIC (Akaike Information Criterion) Comparison
| Model   | Type         | AIC     |
|---------|--------------|---------|
| ARIMA   | Statistical  | 20.42%  |
| SARIMA  | Statistical  | 5.03%   |

Key Insights:

LSTM achieved the best forecasting accuracy with the lowest MAPE.

SARIMA demonstrated the best fit among classical models with the lowest AIC.

📂 Project Structure
├── Applied_forecasting_Code.ipynb    # Main Jupyter notebook with full code and analysis  
├── monthly-oil-production (1).csv      # Folder containing the input CSV data (monthly oil production)  
├── Applied_forecasting_Report.pdf      # Folder with visualizations, plots, and exported results  
└── README.md                          # Project documentation  
⚠️ Disclaimer
Results are subject to variation due to the stochastic nature of model training and parameter tuning. Running the notebook multiple times may yield slightly different MAPE values, especially for deep learning models.

✅ If your model performs better — congratulations!

😌 If results vary — this is expected due to random seeds, training duration, and hardware differences.
