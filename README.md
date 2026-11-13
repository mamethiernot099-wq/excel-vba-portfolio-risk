# Excel/VBA Portfolio Risk Dashboard

Interactive Excel/VBA tool for analysing the performance and market risk of a three-stock equity portfolio.

## Project overview

This academic project was developed as part of the **M1 – Applied Mathematics for Financial Engineering** programme at CY Cergy Paris Université.

The workbook analyses historical daily market data from **2 January 2023 to 31 December 2025** for three CAC 40 stocks:

- TotalEnergies
- BNP Paribas
- LVMH

The dataset contains approximately **766 daily observations**.

The portfolio follows a **Buy and Hold** strategy: the initial quantities of each asset are held constant over the investment horizon, without rebalancing.

## Main features

- Import and organisation of historical stock-price data.
- Calculation of daily asset returns and portfolio returns.
- Portfolio valuation over time.
- Annualised volatility and covariance/correlation analysis.
- Historical Value at Risk (VaR) at the 95% confidence level.
- Rolling VaR based on a 250-observation window.
- Backtesting and monitoring of VaR exceedances.
- Drawdown analysis.
- Automated calculations and dashboard updates using VBA macros.
- Interactive Excel dashboard with financial indicators and charts.

## Selected results

The figures below are those reported in the project's CV/report version and should be interpreted in the context of the historical sample:

| Indicator | Result |
|---|---:|
| Annualised portfolio volatility | 18.82% |
| Historical VaR (95%) | 1.804% |
| Rolling VaR window | 250 observations |
| Observed VaR exceedance rate in backtesting | 5.24% |

## Repository structure

```text
excel-vba-portfolio-risk/
├── workbook/
│   └── portfolio_risk_dashboard.xlsm
├── report/
│   └── project_report.pdf
├── presentation/
│   └── project_presentation.pptx
├── screenshots/
│   └── (dashboard and workbook screenshots)
└── README.md
```

## Tools and methods

- **Microsoft Excel**: data organisation, dashboard and charts.
- **VBA**: automation of calculations and dashboard updates.
- **Financial mathematics and statistics**: returns, volatility, covariance, correlation, VaR and drawdown.
- **Yahoo Finance**: historical market-price data source.

## How to use

1. Download the Excel workbook from the `workbook/` folder.
2. Open it in the desktop version of Microsoft Excel.
3. Enable macros if prompted and if you trust the workbook.
4. Use the workbook's input and update controls to load or refresh data and recalculate the dashboard.

The workbook is macro-enabled (`.xlsm`). Its VBA functionality may not work in Excel for the web or in spreadsheet applications that do not support VBA.

## Disclaimer

This is an academic portfolio-risk analysis project, not investment advice. Historical observations and risk estimates do not guarantee future performance or losses.

## Author

**Mame Thierno Thiam**  
M1 – Applied Mathematics for Financial Engineering  
CY Cergy Paris Université
