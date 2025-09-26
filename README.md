# 📈 StockCast-ARIMA
*A Time Series Forecasting Model for Stock Price Prediction*

## 🔍 Project Overview
StockCast-ARIMA is a time series forecasting project designed to predict stock prices using the **ARIMA (AutoRegressive Integrated Moving Average)** model.  
The project demonstrates how classical statistical models can be applied to financial data for trend analysis and short-term prediction.

---

## 🎯 Objectives
- Collect and preprocess historical stock price data
- Perform exploratory data analysis (EDA)
- Build and tune an ARIMA model using **pmdarima’s auto_arima**
- Forecast stock prices on test data
- Evaluate model accuracy with metrics (RMSE, MAE)
- Generate future predictions for unseen periods

---

## 📊 Dataset
- **Stock**: Example used – Apple Inc. (AAPL)
- **Features**: Date, Open, High, Low, Close, Volume
- **Target Variable**: Closing Price

---

## ⚙️ Tech Stack
- **Python** (3.9+)
- **Libraries**:
  - `pandas`, `numpy` → Data handling
  - `matplotlib` → Visualization
  - `pmdarima` → ARIMA model building
  - `scikit-learn` → Evaluation metrics

---

## 🧑‍💻 Workflow
1. **Data Collection**  
   - Download stock data from Yahoo Finance  
2. **Preprocessing**  
   - Train-test split  
   - Handling missing values  
3. **Exploratory Data Analysis (EDA)**  
   - Trend visualization  
   - Stationarity check  
4. **Modeling**  
   - ARIMA model selection using `auto_arima`  
   - Model fitting on training set  
5. **Evaluation**  
   - Forecasting on test data  
   - RMSE and MAE calculation  
6. **Future Forecasting**  
   - Predict next 30 business days  

---

## 📈 Results
- The ARIMA model was able to capture the trend of stock prices with reasonable accuracy.
- Forecast visualization:  
  Plots:

  <img width="1468" height="987" alt="image" src="https://github.com/user-attachments/assets/e562108d-adff-4f83-9eb7-4ed231411c45" />
  <img width="848" height="679" alt="image" src="https://github.com/user-attachments/assets/98caadf9-3eae-4789-b456-80aeda5d4674" />



---
