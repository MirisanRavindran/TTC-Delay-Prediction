# TTC Delay Prediction

End-to-end ML pipeline predicting Toronto subway delays using historical TTC
incident data and Toronto weather conditions.

## Project structure
├── data/
│   ├── raw/          # Source data (gitignored)
│   └── processed/    # Cleaned data (gitignored)
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_regression.ipynb
│   └── 04_classification.ipynb
├── src/              # Reusable code
├── reports/figures/  # Generated plots
└── requirements.txt

## Data sources

- **TTC Subway Delay Data** — [City of Toronto Open Data Portal](https://open.toronto.ca/dataset/ttc-subway-delay-data/)
- **Historical weather** — [Environment & Climate Change Canada](https://climate.weather.gc.ca/)

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then run the notebooks in order, starting with `01_eda.ipynb`.

## Results

_Coming soon._
