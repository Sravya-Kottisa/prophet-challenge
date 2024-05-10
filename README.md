# MercadoLibre Search Traffic Analysis
## Description:
This project analyzes the hourly Google search traffic data for MercadoLibre, a popular e-commerce platform, to identify unusual patterns, seasonality, and relationships with stock price patterns. The project also creates a time series model using Prophet to forecast search traffic.

## Steps:
1. ***Find Unusual Patterns in Hourly Google Search Traffic:*** 
  - Read search data into a DataFrame and slice to May 2020.
  - Visualize results and identify unusual patterns.
  - Calculate total search traffic and compare to monthly median.
2. ***Mine Search Traffic Data for Seasonality:***
  - Group data by hour of day, day of week, and week of year.
  - Plot average traffic and identify seasonal patterns.
3. ***Relate Search Traffic to Stock Price Patterns:***
  - Read in and plot stock price data.
  - Concatenate stock price data to search data.
  - Slice data to first half of 2020 and plot.
  - Create new columns for lagged search trends, stock volatility, and hourly stock return.
  - Identify relationships between lagged search traffic and stock volatility/returns.
4. ***Create a Time Series Model with Prophet:***
  - Set up search data for Prophet forecasting model.
  - Estimate and plot the forecast.
  - Plot individual time series components to identify:***
    - Time of day with greatest popularity.
    - Day of week with most search traffic.
    - Lowest point for search traffic in the calendar year.
## Dependencies:
- pandas
- matplotlib
- prophet
