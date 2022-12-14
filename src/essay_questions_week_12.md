## Algorithm understanding
1. Prophet is based on additive regression models instead of RNNs like LSTMs. This makes them easier to interpret but perhaps less flexible than a LSTM. Prophet is particularly suited for business data time-series forecasting. LSTM can handle any type of sequential data.
2. LSTMs require large datasets and will tend to overfit smaller datasets unlike ARIMA or Prophet.

## Interview readiness
1. Exponential smoothing assigns exponentially decreasing weights over time to previous data points within a window instead of assigning equal weight to past observations like a simple moving average. It is used in time-series forecasting so models can learn past observations in a compounding manner.
2. Stationarity assumes the statistical properties of the process/thing being observed does not change over time; this doesn't mean that the time-series data from this process cannot change. For example, you might assume stationarity in for a well-established company, but its stock price will vary over time. Seasonality is a component that considers time of year. For example, number of website views might be less in the summer versus the winter.
3. Seasonality is predictable, cyclicality is not. Seasonality are trends that are captured within a calendar year (e.g., summer vs. winter ad views). Cyclicality pertains to business cycles due to supply and demand, which is dependent on the complex confluence economic factors (e.g., supply shortages, government regulation, etc.)
