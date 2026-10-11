# Retail Sales Demand Forecasting & Inventory Intelligence

An exploratory retail demand forecasting and inventory planning project using synthetic data across five stores and twenty products.

## Highlights

- Explores sales patterns and checks data quality.
- Compares baseline, ARIMA, Prophet, Random Forest, and Gradient Boosting forecasts.
- Connects a 30-day demand scenario to safety stock and reorder point estimates.

## Dataset

Provided by **StarAgile for my Data Science capstone project**. The dataset is listed on [Kaggle](https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset) under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). It contains 73,100 rows and 15 original columns.

## Results

| Model | MAE | RMSE |
|---|---:|---:|
| Random Forest | 834.99 | 1,056.53 |
| ARIMA(1,0,0) | 853.36 | 1,061.54 |
| Prophet | 858.41 | 1,074.94 |

The January 2024 scenario forecasts about **411,050 units** over 30 days. Under assumed seven-day lead time and 95% service level, estimated safety stock is **5,011 units** and reorder point is **100,923 units**.

The model comparison is exploratory, and the inventory estimates are aggregate and illustrative—not item-level recommendations.