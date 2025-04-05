# Macroeconomic Shock Simulation

![screenshot-localhost_8888-2025 04 05-15_54_59](https://github.com/user-attachments/assets/7af5347f-7bf2-4197-9913-90c193754d7d)

## Overview

This project provides a Python-based framework for simulating macroeconomic shocks (inflation spikes and currency depreciations) during financial crises. It analyzes historical crisis data to quantify risk exposures and assess portfolio vulnerabilities.

### Data Source

The analysis uses the "global_crisis_data" dataset, which contains historical information on various types of financial crises, sovereign defaults, inflation rates, exchange rates, and other economic indicators across multiple countries and time periods.

### Key Features:

- Realistic shock modeling (hybrid additive/multiplicative impacts)
- Data cleaning pipeline (handling outliers, missing values, and normalization)
- Country-specific risk profiling (identifies most vulnerable economies)
- Interactive visualizations (impact distributions, temporal trends)
- Scenario analysis (baseline vs. stress test scenarios)

### Key Outputs

- Inflation/Exchange Rate Shocks: outputs/shock_results.csv
- Visualizations:
- Pre-shock distributions (outputs/figures/pre_shock_dist.png)
- Crisis impact scatterplots (outputs/figures/impact_analysis.png)

### Key Findings

Median Crisis Impact:
- +4.5pp inflation spike
- 12% currency depreciation

High-Risk Economies:
- Ecuador, Angola, Zimbabwe (hyperinflation-prone)

Data Limitations:
- Exchange rate data covers only 47% of historical crises

### Source

[Global Crisis Dataset from Kaggle](https://www.kaggle.com/datasets/ayush12nagar/global-crisis)
