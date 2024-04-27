# Pharmacy Sales - Seasonality Analysis

![image](https://github.com/poojagotur/Pharmary-Sales-Seasonality-Analysis/assets/138715091/f760a83f-631e-4fbb-ac7a-a9f2c7eb7875)

This project focuses on analyzing seasonal patterns within pharmacy sales data, aiming to provide insights that can optimize staffing and marketing strategies. The research compares contemporary time-series forecasting methods against basic models, utilizing a comprehensive six-year dataset that captures eight distinct drug categories.

## Data

The initial datasets contain six years of transactional records from a pharmacy's Point-of-Sale system. The data includes information such as date, time, pharmaceutical details, and sales quantities. The analysis shifted focus from individual drugs to broader categories under the ATC classification system, resulting in hourly time-series data aggregated into weekly sales for analysis.

## Objective

The project aims to:

1. **Seasonal Patterns:** Explore seasonality and patterns within pharmacy sales data yearly and over the six-year span.
2. **Drug Categories (ATC Classifications):** Investigate variations in seasonality across different drug categories.
3. **Operational Optimization:** Utilize insights for staffing and marketing optimization within the pharmacy.

## Data Modeling Methodology

Model selection relied on comparing forecasting accuracies among models such as Seasonal Naïve, Holt-Winters, ARIMA, AutoARIMA, SARIMA, and Neural Networks. Train-test splits used the last year's data for testing. Performance evaluation centered on Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE), with Neural Networks emerging as the preferred model for most drug categories.

## Model Results and Insights

The results highlighted Neural Networks as the optimal model for most drug categories, ensuring accurate forecasts with lower errors. Recommendations encompass tailored strategies for inventory management, marketing, staffing, and financial planning for each drug category based on forecasting observations.


