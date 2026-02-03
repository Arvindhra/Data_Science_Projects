# LRT & MRT Ridership Forecasting (Malaysia)
## Project Overview

### This project forecasts public transport ridership for four major rail lines in Malaysia:
#### i) LRT Kelana Jaya Line

MRT Kajang Line

LRT Ampang Line

MRT Putrajaya Line

The objective is to understand historical ridership trends and forecast demand for Q1 2026 (January–March 2026) using a time-series forecasting model.

The project was completed in January 2026.

Modeling Approach

The forecasting model used in this project is Facebook Prophet, a decomposable time-series model that captures:

Trend

Seasonality

Holiday effects (optional)

Each rail line is modeled independently, with different training windows based on data availability.

Key Analysis Components

Yearly Ridership Trends
Comparison of total ridership by year for each line.

Monthly Trends by Year (2019–2025)
Comparison of monthly ridership across lines for each year.

Monthly Trends by Line (2019–2025)
Comparison of ridership patterns across years for each line.

Time-Series Forecasting
Prophet models trained separately for each line.

Model Evaluation
Performance evaluated on a hold-out test set using:

Absolute Error (AE)

Absolute Percentage Error (APE)

Mean Absolute Error (MAE)

Mean Absolute Percentage Error (MAPE)

Forecast Period

Training data: Historical ridership up to mid/late 2025

Testing data: Late 2025

Forecast horizon: Q1 2026 (January–March 2026)

Data Source & Attribution

The dataset used in this project is published by the Government of Malaysia through the Open Data Malaysia portal (data.gov.my).

Dataset: Daily Public Transport Ridership
Publisher: Ministry of Transport Malaysia, Prasarana Malaysia
Link: https://data.gov.my/data-catalogue/ridership_headline

The data is used under the Open Data Malaysia License, which permits reuse with attribution.

Disclaimer:
All preprocessing, transformations, and analysis were performed by the project author.
This project is not affiliated with or endorsed by the Government of Malaysia or Prasarana Malaysia.
