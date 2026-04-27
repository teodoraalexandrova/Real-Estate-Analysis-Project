# Real-Estate-Analysis-Project
Impact of Mortgage Rates on Housing Prices

Project Overview:
This project investigates the correlation between macroeconomic factors—specifically 30-year fixed mortgage rates—and residential real estate valuations. By consolidating data from two independent sources, we demonstrate how borrowing costs influence housing market dynamics.

Data Sources:
To comply with the project requirements, data was gathered from two independent providers:
- Housing Market Data: Sourced from Kaggle (Ames Housing Dataset), containing features of residential properties and their sale prices.
- Macroeconomic Data: Sourced from FRED (Federal Reserve Economic Data), providing weekly 30-year fixed-rate mortgage averages in the United States.

Key Features & Methodology:
Data Consolidation: Merging house sales with interest rate data based on the year and month of the transaction.
Mathematical Transformation: Applied a natural log transformation ln(1+x) to the target variable to normalize distribution and handle skewness.
Exploratory Data Analysis (EDA): Visualized correlations and identified the top 10 factors influencing prices.
Predictive Modeling: Implemented a Multiple Linear Regression model to quantify the impact of interest rates.

Mathematical Foundation:
The model is based on the following regression equation:
ln(1 + SalePrice) = b0 + b1 * MortgageRate + b2 * GrLivArea + b3 * OverallQual + epsilon

Conclusions:
The analysis confirmed a measurable correlation between rising mortgage rates and a decrease in property sale prices, validating the hypothesis that macroeconomic constraints significantly impact the real estate sector.
