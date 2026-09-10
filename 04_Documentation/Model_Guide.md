# Model Guide

## Purpose

This guide explains the structure and navigation of the Corporate FP&A Budgeting & Forecasting Model developed for Cascade Outdoor Manufacturing.

The workbook is designed to move from historical financial information to forward-looking forecasts, supporting operational plans, scenario analysis, management reporting, and model quality assurance.

---

# Workbook Navigation

The workbook contains 21 worksheets organized into the following areas:

1. Cover
2. Management Reporting
3. Source Data and Reference Tables
4. Historical Analysis
5. Forecast Assumptions
6. Financial Forecasting
7. Supporting Plans
8. Scenario Analysis
9. Model Quality Assurance

The recommended workflow for reviewing the model is:

```text
Historical Actuals
        ↓
Historical Analysis
        ↓
Forecast Assumptions
        ↓
Financial Forecast
        ↓
Headcount / CapEx / Cash Flow Plans
        ↓
Scenario Analysis
        ↓
Management Reporting
        ↓
Model QA
```

---

# 1. Cover

The `Cover` worksheet serves as the introduction to the model.

It identifies:

- Corporate FP&A Budgeting & Forecasting Model
- Cascade Outdoor Manufacturing
- Historical and forecast periods
- The purpose of the workbook

This worksheet is intended to provide context before reviewing the underlying model.

---

# 2. Control Panel

The `Control Panel` is the primary management-facing worksheet.

It consolidates important financial outputs, forecast drivers, scenario results, model status, and management insights into one location.

The Control Panel includes:

- Model QA Status
- Active Forecast Scenario
- Forecast Period
- Management Forecast Summary
- Forecast Driver Analysis
- Historical-to-Forecast Variance Analysis
- Scenario and Risk Analysis
- Executive KPI Snapshot
- Executive Takeaways
- Final Model Readiness
- Management Decision Support

The Control Panel is designed to answer three primary questions:

1. What is the forecast?
2. What are the major financial drivers and risks?
3. What should management focus on?

For management review, this is the recommended starting point.

---

# 3. Source and Reference Data

The following worksheets provide supporting reference data used throughout the model.

## Accounts

Contains the account structure used to organize financial information.

## Business Units

Contains the business unit reference information used for analysis and reporting.

## Calendar

Provides the historical calendar structure.

## Departments

Contains department-level reference information.

## Financial Statements

Provides the underlying financial statement structure and source financial information.

## Regions

Contains regional reference information.

These worksheets function as supporting infrastructure for the historical and forecasting components of the model.

---

# 4. Historical Analysis

The historical analysis section evaluates financial performance from 2023 through 2025.

## Historical Actuals

Contains the historical financial data used as the starting point for forecasting.

## Historical Trends

Summarizes multi-year financial trends and performance changes.

## Revenue Analysis

Analyzes historical revenue performance across the available business structure.

## Expense Analysis

Analyzes historical operating expense trends.

## Monthly Analysis

Provides monthly-level analysis used to understand historical financial patterns and trends.

The historical analysis establishes the foundation for forecast assumptions and future planning.

---

# 5. Forecast Assumptions

## Assumptions

The `Assumptions` worksheet contains the primary financial drivers used in the forecast and scenario analysis.

Key assumptions include:

- Revenue growth
- Gross margin
- Operating expense growth
- Operating margin

The model includes:

- Historical reference assumptions
- Base Case assumptions
- Best Case assumptions
- Worst Case assumptions

These assumptions drive the financial forecast and scenario outputs.

## Forecast Calendar

The `Forecast Calendar` establishes the time structure for the 2026–2028 forecast period.

---

# 6. Forecast Model

The `Forecast Model` is the core financial forecasting engine.

The model projects financial performance from 2026 through 2028 using the assumptions and historical financial information contained elsewhere in the workbook.

Major forecast areas include:

- Revenue
- Gross profit
- Operating expenses
- Operating income
- Net income
- Profitability metrics
- Supporting financial outputs

The forecast model serves as the central calculation layer that connects the assumptions and supporting schedules to the management reporting outputs.

---

# 7. Supporting Financial Plans

## Headcount Plan

The `Headcount Plan` projects future employee levels and employment-related costs.

The schedule supports the broader financial forecast by incorporating workforce planning into projected operating expenses.

## CapEx Plan

The `CapEx Plan` forecasts planned capital expenditures and related depreciation.

This schedule connects capital investment decisions to the broader financial and cash flow forecast.

## Cash Flow Plan

The `Cash Flow Plan` projects:

- Cash generation
- Capital investment impacts
- Free cash flow
- Ending cash

The cash flow forecast provides a forward-looking view of the company's projected liquidity and financial flexibility.

Because a 2025 historical ending-cash value was not available in the original source data, the model uses a $1,000,000 management planning assumption as the starting cash balance for the forecast period.

---

# 8. Scenario Analysis

The `Scenario Analysis` worksheet evaluates the financial impact of different planning assumptions.

The model includes:

- Best Case
- Base Case
- Worst Case

The scenarios evaluate changes in key drivers such as:

- Revenue growth
- Gross margin
- Operating expense growth
- Operating margin

The scenario analysis allows management to understand the potential range of outcomes and identify the assumptions that have the greatest impact on future financial performance.

Key outputs include:

- Revenue
- Operating income
- Free cash flow

---

# 9. Model QA

The `Model QA` worksheet contains validation and reconciliation checks designed to identify potential model issues.

The QA process includes checks for:

- Historical financial reconciliation
- Forecast reconciliation
- Ending cash validation
- Capital expenditure validation
- Employment cost validation
- Scenario relationship validation

The overall QA result returns `PASS` when the model checks are satisfied.

The QA status is also carried into the Control Panel to provide a management-facing readiness indicator.

---

# Recommended Review Process

For a management-level review:

```text
Cover
   ↓
Control Panel
   ↓
Scenario Analysis
   ↓
Model QA
```

For a detailed FP&A review:

```text
Historical Actuals
   ↓
Historical Trends
   ↓
Assumptions
   ↓
Forecast Model
   ↓
Headcount Plan
   ↓
CapEx Plan
   ↓
Cash Flow Plan
   ↓
Scenario Analysis
   ↓
Model QA
```

---

# Model Design Philosophy

The workbook was designed around an integrated FP&A workflow rather than as a collection of independent spreadsheets.

The model connects:

**Historical Performance → Financial Assumptions → Forecast → Supporting Plans → Scenario Analysis → Management Reporting → Model QA**

This structure allows financial and operational assumptions to flow through the model and ultimately support management planning and decision-making.
