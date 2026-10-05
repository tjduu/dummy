# Predicting Weekly Bacterial Abundance Across Years

This repository contains the OCES 5303 assignment notebook. It predicts weekly log10 bacterial abundance and classifies samples as Low or High using a seasonal baseline, Ridge regression, and support vector regression. Model performance is evaluated by rotating the held-out year across a three-year coastal time series.

## Files

- `ass1_oces5303_20601408.ipynb` — complete analysis and results
- `requirements.txt` — required Python packages

The notebook downloads the course dataset directly from its public GitHub source.

## Run

Use Python 3.10, install the dependencies, then restart the notebook kernel and run all cells:

```bash
pip install -r requirements.txt
```

## Data source

[OCES 5303 weekly environmental data](https://github.com/julianmak/OCES4303_ML_ocean/blob/main/PIDweekly_env_data.txt)
