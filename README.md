# Revenue Forecasting Project

This project demonstrates how to forecast quarterly revenue for a business based on historical sales data using **Facebook Prophet**, a powerful time series forecasting tool.

---

## Dataset

The dataset contains quarterly aggregated sales revenue:

| ds         | y          |
|------------|------------|
| 2014-03-31 | 22656.1390 |
| 2014-06-30 | 28063.7496 |
| 2014-09-30 | 41957.8783 |
| 2014-12-31 | 64515.0862 |
| 2015-03-31 | 27374.0986 |

- `ds`: Date of the quarter end
- `y`: Total sales revenue for that quarter

---

## Project Overview

The goal is to predict future quarterly revenue to assist business planning and decision-making by:

- Loading historical quarterly sales data
- Fitting a Prophet time series forecasting model
- Evaluating forecast accuracy using MAE and RMSE
- Visualizing actual vs forecasted revenue

---

## Results

- **Mean Absolute Error (MAE):** 4620.33  
- **Root Mean Squared Error (RMSE):** 6298.06

These metrics indicate that on average the forecasts deviate by around 4,620 units, with some larger deviations accounted for by RMSE.

---
