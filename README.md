# Demand forecasting and pricing take-home

All of the analysis is in `Demand_Pricing_Analysis.ipynb`: data cleaning, the demand forecast and backtest, the elasticity estimate, the Q1-2025 pricing recommendation, and a one-page summary for the commercial team (section 7).

## Running it

```
pip install -r requirements.txt
jupyter notebook Demand_Pricing_Analysis.ipynb
```

Then use Kernel > Restart & Run All. It takes a few seconds. The cleaned data and the main result tables are written to `outputs/`.

## Files

- `Demand_Pricing_Analysis.ipynb`: the analysis
- `demand_panel.csv`: the original data, unchanged
- `requirements.txt`: the Python packages needed
- `outputs/`: the cleaned panel, cleaning log, backtest scores, Q1 forecast, elasticity estimates and the pricing table
