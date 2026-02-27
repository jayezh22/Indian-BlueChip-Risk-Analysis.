# Indian Blue-Chip Stocks: Risk-Return Analysis (2020-2025)

## Project Overview
This project provides a quantitative evaluation of investment efficiency for three major Indian blue-chip stocks: **Reliance Industries**, **Tata Consultancy Services (TCS)**, and **HDFC Bank**. By analyzing historical price data from January 2020 to December 2025, the model identifies which assets offer the best risk-adjusted returns using the Sharpe Ratio.

## Key Financial Metrics
The following metrics were calculated using daily historical close prices:

| Company | Avg Daily Return | Volatility (Risk) | Sharpe Ratio |
| :--- | :--- | :--- | :--- |
| **Reliance** | 0.07% | 1.79% | **0.04** |
| **TCS** | 0.04% | 1.51% | **0.03** |
| **HDFC** | 0.04% | 1.62% | **0.02** |

## Technical Implementation
The analysis was performed using Excel/Google Sheets and follows these steps:
1. Data Aggregation:- Compiled five years of historical price data for each stock.
2. Statistical Modeling:- Calculated **Daily Log Returns** to measure asset growth.
   - Determined **Volatility** via standard deviation of returns to quantify market risk.
   - Computed the **Sharpe Ratio** (Return / Volatility) to normalize performance against risk.
3. Visualization:-Developed a scatter plot dashboard with a trendline regression to visualize the "Efficient Frontier" of the portfolio.



## Key Insights
* Relianceis the portfolio leader in terms of efficiency, providing a **0.04** Sharpe Ratio. Its higher volatility is sufficiently compensated by its superior daily returns.
* TCS serves as the defensive anchor with the lowest volatility (**1.51%**), ideal for risk-averse strategies.
* HDFC Bank was identified as relatively inefficient compared to TCS, as it carries higher risk (**1.62%**) for the same average return (**0.04%**).

## File Structure
- `Indian Blue-Chip Stocks Analysis.xlsx`: The core analytical model containing data tabs and the final dashboard.
- `README.md`: Project documentation and executive summary.

---
**Author:** Jayesh Chandekar
**Tools Used: Google Sheets, Excel, Financial Modeling, Quantitative Analysis

<img width="1149" height="489" alt="Screenshot 2026-02-27 205218" src="https://github.com/user-attachments/assets/66fa66bc-0448-4431-b0d0-3d1966817a5a" />

