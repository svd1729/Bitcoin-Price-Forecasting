# Bitcoin-Price-Forecasting
## Introduction
Time series forecasting is a vital tool in data science used to predict future values based on historical trends. Unlike standard machine learning tasks, time series data involves sequential dependencies, trends, seasonality, and noise.

The cryptocurrency market, especially Bitcoin, presents a uniquely complex and volatile environment for forecasting. Its price is influenced by a combination of market sentiment, global events, and 24/7 trading activity. In this project, we apply the classical ARIMA (AutoRegressive Integrated Moving Average) model to predict Bitcoin’s daily closing prices. ARIMA is a well-established technique for univariate forecasting, and this project aims to evaluate its performance as a baseline model before exploring more advanced methods. After that we compared our ARIMA model with facebook's advanced Prophet Model which is considered to be one of the best models for forecasting prices. As expected the Prophet model outperformed our self-made ARIMA model but with a little margin.

## Project Workflow
### step-1: Data Collection
• Historical Bitcoin price data was gathered from Kaggle datasets.

### step-2: Exploratory Data Analysis (EDA)
• Visualized trends, seasonality, and volatility in the data.

• Checked for missing values and ensured data consistency.

### step-3: Data Preprocessing
• Converted the series into a stationary format using differencing.

• Applied log transformations to reduce volatility.

### step-4: Model Building
• Used the ARIMA model for univariate time series forecasting.

• Determined optimal (p, d, q) parameters.

### step-5: Model Evaluation
• Evaluated forecasting accuracy using metrics like MAE, RMSE, and visual comparison.

### step-6: Results & Conclusion
• Analyzed model performance.

• Discussed strengths and limitations of ARIMA in handling highly volatile data like Bitcoin.
