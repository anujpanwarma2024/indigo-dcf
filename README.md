# Indigo DCF — InterGlobe Aviation War Scenario Stress Test

A discounted cash flow (DCF) valuation model for **InterGlobe Aviation Ltd (NSE: INDIGO)** with geopolitical/war scenario stress testing.

## What This Is

This notebook builds a full analyst-style DCF for IndiGo and stress-tests it against three scenarios:

- **Base Case** — Crude at $85, load factor 87%, revenue growth 12%
- **Oil Shock** — Gulf conflict escalation drives crude to $120, fuel costs +35%
- **Demand Collapse** — Regional conflict suppresses travel demand, load factor drops to 72%

## Contents

- `indigo_dcf.ipynb` — Main Jupyter notebook with all model logic, charts, and output
- `requirements.txt` — Python dependencies

## Setup

```bash
pip install -r requirements.txt
jupyter notebook indigo_dcf.ipynb
```

## Key Assumptions

- WACC: 11% (INR-denominated, Indian aviation risk premium)
- Terminal growth rate: 4.5%
- Projection period: 5 years
- Data sourced live from Yahoo Finance via `yfinance`

## Disclaimer

This model is for educational and research purposes only. It does not constitute financial advice.
