# Assumptions and Methodology

## Overview

This document explains the primary assumptions and modeling methodology used in the Corporate FP&A Budgeting & Forecasting Model for Cascade Outdoor Manufacturing.

The model uses historical financial performance from 2023–2025 as the foundation for a three-year forecast covering 2026–2028.

The forecast is built using management-defined assumptions and is evaluated through Base, Best, and Worst Case scenarios.

---

# Forecast Period

## Historical Period

2023–2025

Historical financial performance is used to establish trends and provide the starting point for future planning assumptions.

## Forecast Period

2026–2028

The forecast projects three years of future financial performance.

---

# Scenario Framework

The model includes three forecast scenarios.

## Base Case

The Base Case represents the primary management planning scenario.

It assumes continued revenue growth, stable-to-improving profitability, controlled operating expense growth, and continued positive cash generation.

## Best Case

The Best Case represents a more favorable business environment.

It assumes:

- Higher revenue growth
- Improved gross margin
- Lower operating expense growth
- Improved operating performance

## Worst Case

The Worst Case represents a more challenging business environment.

It assumes:

- Lower revenue growth
- Reduced gross margin
- Higher operating expense growth
- Lower operating performance

The scenario framework is intended to help management understand the potential range of financial outcomes rather than predict a single guaranteed result.

---

# Revenue Growth Assumptions

Revenue growth assumptions are applied to the prior year's forecast revenue.

| Scenario   | Revenue Growth |
| ---------- | -------------: |
| Historical |           7.9% |
| Base Case  |           7.9% |
| Best Case  |          10.9% |
| Worst Case |           4.9% |

The Base Case assumes continued growth consistent with the selected planning assumptions.

The Best and Worst Cases provide an upside and downside range around the primary forecast.

---

# Gross Margin Assumptions

Gross margin assumptions are used to project gross profit relative to forecast revenue.

| Scenario   | Gross Margin |
| ---------- | -----------: |
| Historical |        41.5% |
| Base Case  |        41.5% |
| Best Case  |        42.5% |
| Worst Case |        40.5% |

The Base Case assumes a stable gross margin.

The Best Case assumes operational improvement, while the Worst Case reflects potential margin pressure.

---

# Operating Expense Growth Assumptions

Operating expenses are forecast using annual growth assumptions.

| Scenario   | OpEx Growth |
| ---------- | ----------: |
| Historical |        5.0% |
| Base Case  |        5.0% |
| Best Case  |        3.0% |
| Worst Case |        7.0% |

The Best Case assumes greater expense efficiency, while the Worst Case assumes higher expense growth.

---

# Operating Margin Assumptions

Operating margin assumptions provide an additional planning and scenario framework for evaluating profitability.

| Scenario   | Operating Margin |
| ---------- | ---------------: |
| Historical |            20.9% |
| Base Case  |            20.9% |
| Best Case  |            22.4% |
| Worst Case |            19.4% |

These assumptions support the broader analysis of profitability across the forecast scenarios.

---

# Revenue Forecasting Methodology

The revenue forecast uses annual growth assumptions applied to the previous year's revenue.

The process is:

```text
Prior Year Revenue
        ×
(1 + Revenue Growth Assumption)
        ↓
Forecast Revenue
```

This methodology creates a compounding annual forecast across the 2026–2028 planning period.

---

# Gross Profit Methodology

Gross profit is calculated using forecast revenue and the applicable gross-margin assumption.

The process is:

```text
Forecast Revenue
        ×
Gross Margin Assumption
        ↓
Gross Profit
```

The gross profit calculation allows changes in revenue and margin assumptions to flow through the broader profitability forecast.

---

# Operating Expense Methodology

Operating expenses are projected using annual growth assumptions.

The process is:

```text
Prior Year Operating Expense
        ×
(1 + OpEx Growth Assumption)
        ↓
Forecast Operating Expense
```

This approach allows operating costs to increase at different rates across scenarios.

---

# Headcount Planning Methodology

The Headcount Plan projects future employee levels across the forecast period.

Headcount assumptions are used to estimate future workforce requirements and employment-related costs.

The purpose of the schedule is to connect operational workforce planning with the financial forecast.

The final model projects headcount growth from approximately 92 historical employees to 107 employees by 2028.

Management should evaluate whether workforce growth remains appropriately aligned with projected revenue growth and operational capacity.

---

# Capital Expenditure Methodology

The CapEx Plan forecasts planned capital investment across the forecast period.

The schedule is used to:

- Plan future capital investment
- Estimate depreciation associated with planned assets
- Incorporate investment requirements into the financial forecast
- Evaluate the impact of capital spending on cash flow

The 2028 forecast includes approximately $475,000 in planned capital expenditures.

Capital expenditures should support growth, operating capacity, efficiency, or other strategic requirements.

---

# Cash Flow Methodology

The Cash Flow Plan projects future cash generation and liquidity.

Key outputs include:

- Operating cash generation
- Capital expenditure impacts
- Free cash flow
- Ending cash

Free cash flow provides an indication of the cash available after operating requirements and planned capital investment.

Because the original historical source data did not contain a 2025 ending-cash balance, the model uses a $1,000,000 management planning assumption as the starting cash balance for the forecast period.

This assumption is explicitly treated as a planning input rather than a historical actual.

---

# Scenario Methodology

The scenario analysis evaluates how changes in key assumptions affect projected financial outcomes.

The primary drivers evaluated include:

1. Revenue growth
2. Gross margin
3. Operating expense growth
4. Operating margin

The Best, Base, and Worst Case assumptions flow through the financial model to produce different projected outcomes.

The primary scenario outputs include:

- Revenue
- Operating income
- Free cash flow

For 2028, the model produces the following approximate range:

| Scenario   | Revenue | Operating Income | Free Cash Flow |
| ---------- | ------: | ---------------: | -------------: |
| Best Case  |  $6.63M |           $2.82M |         $2.70M |
| Base Case  |  $6.11M |           $2.53M |         $2.41M |
| Worst Case |  $5.61M |           $2.27M |         $2.15M |

The scenario analysis is intended to support management discussion around forecast risk and planning sensitivity.

---

# Variance Analysis Methodology

The model compares forecast performance with historical financial results.

The purpose is to identify:

- Changes in revenue
- Changes in profitability
- Changes in operating expenses
- Changes in financial performance over time

Variance analysis helps connect the forward-looking forecast to the company's historical performance.

---

# Model QA Methodology

The model includes automated validation checks to help identify potential issues.

The QA process evaluates:

- Historical reconciliation
- Forecast reconciliation
- Ending cash
- Capital expenditures
- Employment costs
- Scenario relationships

The master QA status returns `PASS` when all relevant checks are satisfied.

The QA process is intended to provide a final control layer before the model is used for management reporting.

---

# Key Model Limitations

This project was developed as a portfolio and educational model using a fictional company and illustrative financial data.

The model should not be interpreted as:

- A valuation
- Investment advice
- An audited financial statement
- A prediction of actual company performance

Actual corporate FP&A models would typically incorporate additional factors such as:

- Monthly actual-versus-budget reporting
- Rolling forecasts
- Department-level budgets
- Detailed workforce assumptions
- Working capital schedules
- Debt schedules
- Tax planning
- Foreign exchange impacts, where applicable
- Additional approval and governance processes

The purpose of this project is to demonstrate the core workflow and financial modeling skills involved in corporate FP&A planning and forecasting.
