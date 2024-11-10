

# Stock Market Analysis and Prediction

### Project Overview
This project focuses on analyzing historical stock market data and building predictive models to forecast future stock prices. The analysis includes data preprocessing, exploratory data analysis (EDA), and predictive modeling using techniques like linear regression and time series forecasting.

### Project Objectives
- Fetch and analyze historical stock data.
- Perform data preprocessing and feature engineering.
- Visualize stock trends and key indicators.
- Build and evaluate predictive models to forecast future stock prices.

---

### Table of Contents
1. [Project Setup](#project-setup)
2. [Data Collection](#data-collection)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Predictive Modeling](#predictive-modeling)
6. [Advanced Analysis](#advanced-analysis)
7. [Requirements](#requirements)
8. [Resources and References](#resources-and-references)

---

### Project Setup
To set up and run this project, clone the repository and manually install the required libraries listed in the **Requirements** section.

```bash
git clone https://github.com/tina-2002/stockmarket_analysis.git
cd stockmarket_analysis
```

### Data Collection
Historical stock data is retrieved using the `yfinance` library. In this project, we analyze Apple Inc. (AAPL) stock data from 2018 to 2024. You can modify the stock symbol and time frame in the code to analyze other stocks.

### Data Preprocessing
1. **Missing Values**: Checked for and filled missing data using forward fill.
2. **Feature Engineering**: Added 50-day and 200-day moving averages for trend analysis.

### Exploratory Data Analysis
We visualized the following:
- **Close Price**: Historical close prices over time.
- **Moving Averages**: 50-day and 200-day moving averages to identify trends.

### Predictive Modeling
A linear regression model was built to predict the next day's closing price using the following features:
- **Close Price**
- **50-Day Moving Average**
- **200-Day Moving Average**

The model was evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**

### Advanced Analysis (Optional)
For more advanced predictions, you can experiment with:
- **ARIMA Model**: Time series forecasting.
- **LSTM Neural Network**: Deep learning-based stock price prediction (TensorFlow/Keras).

---

### Requirements
- Python 3.10
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `yfinance`

To install these libraries, use:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance
```

### Resources and References
- [Yahoo Finance API (via yfinance)](https://pypi.org/project/yfinance/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html) for Linear Regression
- [Statsmodels](https://www.statsmodels.org/stable/index.html) for ARIMA
- [TensorFlow/Keras](https://www.tensorflow.org/) for deep learning with LSTM (optional)

---

### Results and Observations
This project demonstrates how stock data can be leveraged to understand trends and build models for basic price predictions. While linear regression provides a foundation, advanced models like ARIMA and LSTM can capture more complex time-series behaviors.

### Contributing
Feel free to fork this repository, submit issues, and make pull requests to improve the project.
