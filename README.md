#### AIRLINE PASSENGER (TIME-SERIES) PREDICTION USING LSTM

I'm using LSTM deep learning model for this project. The Long Short-Term Memory network, or LSTM network, is a recurrent neural network that is trained using Backpropagation through time and overcomes the vanishing gradient problem. LSTM can be used to create large recurrent networks that in turn can be used to address diCcult sequence problems in machine learning and achieve state-of-the-art results. Instead of neurons, LSTM networks have memory blocks that are connected through layers.

Aim of the project:
Given the number of passengers (in units of thousands) for last two months, what is the number of passengers next month? In order to solve this problem we will build a LSTM model and train this model with our train data which is Jrst 100 months in our dataset. After the LSTM model training Jnishes and learn the pattern in time series train data.
  
#### 1. Introduction to Time-Series Analysis
A time-series data is a series of data points or observations recorded at different or regular time intervals. In general, a time series is a sequence of data points taken at equally spaced time intervals. The frequency of recorded data points may be hourly, daily, weekly, monthly, quarterly or annually.
Time-Series Forecasting is the process of using a statistical model to predict future values of a time-series based on past results.
A time series analysis encompasses statistical methods for analyzing time series data. These methods enable us to extract meaningful statistics, patterns and other characteristics of the data. Time series are visualized with the help of line charts. So, time series analysis involves understanding inherent aspects of the time series data so that we can create meaningful and accurate forecasts.
Applications of time series are used in statistics, Jnance, business applications, sales and demand forecasting, weather forecasting, econometrics, signal processing, pattern recognition and earthquake prediction.
Components of a Time-Series
Trend - The trend shows a general direction of the time series data over a long period of time. A trend can be increasing(upward), decreasing(downward), or horizontal(stationary).
Seasonality - The seasonality component exhibits a trend that repeats with respect to timing, direction, and magnitude. Some examples include an increase in water consumption in summer due to hot weather conditions.
Cyclical Component - These are the trends with no set repetition over a particular period of time. A cycle refers to the period of ups and downs, booms and slums of a time series, mostly observed in business cycles. These cycles do not exhibit a seasonal variation but generally occur over a time period of 3 to 12 years depending on the nature of the time series.
Irregular Variation - These are the cuctuations in the time series data which become evident when trend and cyclical variations are removed. These variations are unpredictable, erratic, and may or may not be random.
ETS Decomposition - ETS Decomposition is used to separate different components of a time series. The term ETS stands for Error, Trend and Seasonality.

#### 2. Types of Data
The time series analysis is the statistical analysis of the time series data. A time series data means that data is recorded at different time periods or intervals. The time series data may be of three types:
1) Time series data --> The observations of the values of a variable recorded at different points in time is called time series data.
2) Cross sectional data --> It is the data of one or more variables recorded at the same point in time.
3) Pooled data --> It is the combination of time series data and cross sectional data.

#### 3. Time Series Terminology
There are various terms and concepts in time series that we should know. These are as follows:
1) Dependence- It refers to the association of two observations of the same variable at prior time periods.
2) Stationarity --> It shows the mean value of the series that remains constant over the time period. If past effects accumulate and the values increase towards inJnity then stationarity is not met.
3) Differencing --> Differencing is used to make the series stationary and to control the auto- correlations. There may be some cases in time series analyses where we do not require differencing and over-differenced series can produce wrong estimates.
4) SpeciJcation --> It may involve the testing of the linear or non-linear relationships of dependent variables by using time series models such as ARIMA models.
5) Exponential Smoothing --> Exponential smoothing in time series analysis predicts the one next period value based on the past and current value. It involves averaging of data such that the non-systematic components of each individual case or observation cancel out each other. The exponential smoothing method is used to predict the short term prediction.
6) Curve Jtting --> Curve Jtting regression in time series analysis is used when data is in a non-linear relationship.
7) ARIMA --> ARIMA stands for Auto Regressive Integrated Moving Average.
