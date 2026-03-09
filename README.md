# CME Group DCF Valuation Model

Full discounted cash flow valuation of CME Group (NASDAQ: CME) 
built in Python using live financial data.

## Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, yFinance)
- DCF modeling, terminal value, sensitivity analysis
- Live data pulled via Yahoo Finance API

## Model Components
- Historical revenue and operating margin analysis (2022–2025)
- 5-year revenue and free cash flow projections
- WACC-based discounting and terminal value calculation
- Implied share price vs current market price
- Sensitivity analysis across WACC and terminal growth assumptions

## Key Findings
- Base case implied share price: $197.52 vs market price of $319.64
- CME operating margins expanded from 60.2% to 64.9% (2022–2025)
- Asset-light model with CapEx/Revenue ratio of ~1.3%
- Market price consistent with ~7% WACC and 3.5% terminal growth rate

## Data Source
Yahoo Finance API — CME Group financials, pulled March 2026
