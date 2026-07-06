# 📈 Uber Stock Price Prediction using Machine Learning

<p align="center">
  <img src="images/banner.png" width="100%">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-blue?style=for-the-badge&logo=plotly)

</p>

---

# 📌 Project Overview

This project focuses on predicting the **daily closing stock price of Uber Technologies Inc.** using historical stock market data and Machine Learning algorithms.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Training
- Model Evaluation
- Best Model Selection
- Model Saving (.pkl)

---

# 📂 Dataset Information

Dataset contains historical Uber stock prices.

| Column | Description |
|---------|-------------|
| Date | Trading Date |
| Open | Opening Price |
| High | Highest Price |
| Low | Lowest Price |
| Close | Closing Price |
| Adj Close | Adjusted Closing Price |
| Volume | Number of Shares Traded |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-Learn
- Joblib

---

# 📊 Exploratory Data Analysis

The project includes several visualizations:

- Closing Price Trend
- Trading Volume Analysis
- Open vs Close Price
- High vs Low Price
- Distribution of Closing Price
- Correlation Heatmap
- Moving Average
- Actual vs Predicted Price
- Feature Importance

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

The best-performing model is automatically selected based on **R² Score** and saved as:

```
best_stock_model.pkl
```

---

# 📈 Model Evaluation

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

# 📁 Project Structure

```
Uber-Stock-Price-Prediction/
│
├── data/
│   └── uber_stock.csv
│
├── images/
│   ├── closing_price.png
│   ├── volume_trend.png
│
├── notebooks/
│   └── Stock_Price_Prediction.ipynb
│
├── models/
│   ├── best_stock_model.pkl
│   └── features.pkl
│
├── requirements.txt
├── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Uber-Stock-Price-Prediction.git
```

Go to project folder

```bash
cd Uber-Stock-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

# 📸 Project Preview

## Closing Price Trend

![Closing Price](images/closing_price.png)

---

## Trading Volume

![Volume](images/volume_trend.png)

---

## Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

---

## Moving Average

![Moving Average](images/moving_average.png)

---

## Actual vs Predicted

![Prediction](images/actual_vs_predicted.png)

---

# 💡 Key Insights

- Uber stock prices showed significant fluctuations during the observed period.
- Opening price has a strong relationship with the closing price.
- Trading volume varies considerably across trading sessions.
- Random Forest achieved the best prediction performance among the evaluated models.
- Machine Learning models effectively captured historical price patterns.

---

# 🔮 Future Improvements

- XGBoost Regressor
- CatBoost Regressor
- LSTM Time Series Forecasting
- Streamlit Web Application
- Live Stock Data Integration
- Technical Indicators (RSI, MACD, Bollinger Bands)

---

# 👨‍💻 Author

**Nikhil Dongare**

📧 Email: your-email@example.com

🔗 GitHub: https://github.com/Nikhildongare123

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
