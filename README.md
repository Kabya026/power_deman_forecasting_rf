# power_deman_forecasting_rf

# Power Demand Forecasting using Random Forest

This project is about predicting the next hour’s electricity demand using past demand values and simple time-based features.

I used a Random Forest model for prediction and created features like previous hour demand, previous day same hour demand, and rolling average.

## Features used
- lag_1
- lag_24
- rolling_mean_24
- hour
- dayofweek
- month

## Result
The final test MAPE obtained was **6.04%**.

From the feature importance, it can be seen that the previous hour demand and previous day demand were the most useful features.

Overall, the model performs reasonably well and is able to capture short-term demand trends.
