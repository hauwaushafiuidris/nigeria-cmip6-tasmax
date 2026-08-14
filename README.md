# Nigeria CMIP6 TASMAX Analysis

## Overview

This project explores mean maximum air temperature (TASMAX) across Nigerian states using CMIP6 climate data.

The current dataset contains state-level TASMAX values for July 2020 under three CMIP6 scenarios:

- SSP1-1.9
- SSP2-4.5
- SSP3-7.0

## Dataset

The dataset contains:

- 37 Nigerian locations (36 states + FCT)
- 3 CMIP6 scenarios
- Mean TASMAX in °C
- July 2020

## Analysis

The Jupyter Notebook includes:

- Data inspection and quality checks
- Scenario-level summary statistics
- State-level TASMAX ranking
- Scenario comparison
- State × scenario heatmap

## Key Results

The July 2020 dataset has an overall mean TASMAX of approximately **32.5°C**.

State-level values range from approximately **29.4°C to 35.6°C**.

The three scenarios have very similar mean TASMAX values for this particular period.

## Important Limitation

The current dataset represents **July 2020 only**.

It should therefore **not** be interpreted as a 2020–2039 time-series analysis. Future versions can incorporate the complete 2020–2039 period.

## Project Structure

```text
nigeria-cmip6-tasmax/
│
├── nigeria_tasmax_cmip6.ipynb
├── nigeria_tasmax_clean.csv
└── README.md
