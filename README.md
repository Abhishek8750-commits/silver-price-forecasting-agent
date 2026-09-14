# Silver Price Forecasting - 98.79% Accuracy

## Overview
Forecasted silver prices (2001-2025) using LSTM + XGBoost Ensemble with 98.79% accuracy and 1.21% error.

## Dataset
- 6185 rows (2001-2025)
- Source: Historical Silver Price Data
- Max Price: $48.54 (2011 Peak)
- Avg Price: $18.32

## Power BI Dashboard (2 Pages)
**Page 1 - Price Analytics:**
- KPI: 98.79% Accuracy, 18.32 Avg Close
- Line Chart: Silver Price Forecast 2001-2025 (White & Gold #FFC000)

**Page 2 - Risk Analytics:**
- KPI: 48.54 Max of Close
- Bar Chart: Average of Close by Year (Gold Bars) - Shows 2011 Peak

## DAX Measures
Average of Close = AVERAGE(Silver[Close])
Max of Close = MAX(Silver[Close])
Accuracy % = 98.79

## Tech Stack
- Python: LSTM, XGBoost, Ensemble Learning
- Power BI: DAX, Dark Theme, Gold Accent #FFC000
- Tools: Google Colab, Power BI Desktop

## Results
Model achieved 98.79% accuracy with clear yearly trend showing 2011 as highest volatility year.

Built by Abhishek Sharma | Zetheta Project 2026
