# Bitcoin-close-price-regression
This is a group project in a Machine Learning coursework, UEH university. The goal of this project is to build a model that can predict close price of Bitcoin in the next day based on historical data.
## Project overview
### 1. Data acquisition
- Bitcoin historical data, S&P500 index and Gold price is collected from Yahoo Finnance and stored in a CSV file
### 2. Data pre-processing
- Handle missing values with forward fills
- Unit root testing to check stationarity
- Apply logarithm transformation on data
- Apply Min-Max Scaler on data
- Feature engineering technical analysis index with Bitcoin data
### 3. Model Training
- Used models: ARIMA, Regression Tree, Long-Short Term Memory (LSTM)
- Train/test split with 85/15 ratio
- Perform sliding window analysis technique on training and testing data
- Hyper-parameters tuning with Grid Search technique
### 4. Model evaluation
- Evaluate model's performance on testing data
- Metrics to evaluate models performance include: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), R-Squared
