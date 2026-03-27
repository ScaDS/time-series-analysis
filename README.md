# Time Series Analysis

A practical introduction to time series analysis and forecasting using Python.

The notebooks can be viewed as Jupyter Book at: <https://scads.github.io/time-series-analysis/>

## How to run

Install [uv](https://docs.astral.sh/uv/)

```bash
uv sync
uv run jupyter lab
```

## How to build and start the book locally

[Jupyter Book v2](https://jupyterbook.org/) is used.

```bash
uv run jupyter book build
```

The rendered HTML is written to `_build/html/`.

```bash
uv run jupyter book start
```

The rendered book can be viewed in your browser via `http://localhost:3000`