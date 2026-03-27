# Time Series Analysis - Overview

A practical introduction to time series analysis and forecasting using Python,
illustrated with real climate data from the German Weather Service (DWD).

## Contents

| Notebook | Topic |
|---|---|
| [00 - Load DWD Data](00_load-dwd-data.ipynb) | Fetching and preparing weather station data |
| [01 - Time Series Properties](01_time-series-properties.ipynb) | Stationarity, seasonality, autocorrelation |
| [02 - Traditional Methods](02_tsa-traditional.ipynb) | ARIMA, exponential smoothing, classical decomposition |
| [03 - ML & Deep Learning](03_tsa-ml-dl.ipynb) | Tree-based and deep learning methods with Darts |
| [04 - AutoML](04_automl.ipynb) | Automated model selection with AutoGluon |
| [05 - Transformers](05_tsa-transformer.ipynb) | Temporal Fusion Transformer with Darts |

## Data

All examples use hourly/daily temperature and precipitation records from five DWD
climate stations across Germany.

## How to run

Install [uv](https://docs.astral.sh/uv/)

```bash
uv sync
uv run jupyter lab
```
