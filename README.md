# sales-revenue-forecasting


Project Overview

Accurately forecasting revenue is a critical challenge for retail and supermarket organizations, as it directly impacts pricing strategies, inventory planning, promotions, and overall business decision-making. Many organizations lack the technical expertise or resources to build reliable forecasting models using historical and market data.

This project addresses that gap by applying regression-based machine learning techniques to historical retail sales data. Using Walmart’s historical sales dataset, we analyze key internal and external factors influencing revenue and build a Random Forest Regression model to predict weekly sales with high accuracy.

The primary goals of this project are to:
- Identify the key factors influencing retail revenue
- Evaluate which features contribute most to sales forecasting
- Assess the accuracy of regression models in predicting future revenue
- Understand the role of external market indicators such as fuel price, unemployment, CPI, and holidays


Dataset Description:
- Source: Walmart Sales Dataset (Kaggle)
- Time Period: 2010–2012
- Observations: 6,436 rows
- Features: 8 original variables



Exploratory Data Analysis (EDA)

- Scatter plots and summary statistics were used to analyze relationships between weekly sales and:
- Temperature
- Fuel Price
- CPI
- Unemployment
- Holiday Weeks

The analysis showed that most relationships were non-linear, motivating the use of a tree-based regression model rather than simple linear regression.
This project demonstrates that machine learning regression models, particularly Random Forests, can be highly effective for retail revenue forecasting when historical sales data is leveraged. While external market factors provide contextual value, historical trends remain the most reliable indicator of future performance.
