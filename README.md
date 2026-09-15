# Silver Commodity Price Forecasting Agent - ZeTheta Project 1D

## Project Overview
End-to-end Silver (XAG/USD) Price Forecasting with Risk Analytics and Power BI Dashboard

## Metrics Achieved
- XGBoost Accuracy: 94.86%
- RMSE: 1.95, MAPE: 5.14%
- Last 90 Days Accuracy: 93.08%
- VaR 95%: -2.97%, GARCH Volatility: 1.85%
- Trading Signal: BUY (Accuracy >90%)

## Models Compared
- ARIMA/SARIMA, Facebook Prophet, LSTM (2-layer 50 units), XGBoost (200 estimators), Ensemble (0.6*XGB+0.25*LSTM+0.15*Prophet)

## Datasets Merged (6185 Rows)
6 files merged using pandas merge_asof: OHLC Daily, Macro (DXY, Gold), COT Report, VIX Index, Futures Curve, Supply Demand

## Power BI Dashboard - 4 Pages
1. Overview: Avg Close $17.62, XGB $18.64, Year-wise trend
2. Risk Analysis: VaR -2.97%, GARCH 1.85%, RMSE 1.95
3. Model Performance: Year table, KPI 47.83 Goal 47.22, Actual vs Predicted 94.86%
4. Trade Signals: BUY Signal, Date Slicer 2000-2025, Gold vs DXY vs VIX Impact

## DAX Measures
Avg_Close, XGB_Avg, Accuracy, Last90D_Acc=93.08%, VaR_95=-2.97%

## Files
- ZeTheta_Silver_FINAL_4Pages.pdf (Dashboard)
- ZeTheta_COMBINED_FINAL_3Files.pdf (Dashboard+Report for Evaluation)
- silver_FULL_6185_rows_FINAL.csv
- Silver_Forecasting_StepByStep.ipynb
