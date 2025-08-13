# NBA Player Impact Study

Automated pipeline to collect, clean, and analyze 10+ seasons of NBA player data, with an interactive dashboard for recurring performance reporting.

## Highlights
- Automated data collection + cleaning (API → tidy tables)
- Correlation/regression to identify win-share predictors
- Tableau dashboard for recurring analysis
- Reproducible scripts + notebooks

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python src/get_data.py
python src/clean_data.py
jupyter notebook notebooks/01_explore.ipynb
```

## Structure
```
src/                # ETL + analysis scripts
notebooks/          # EDA and presentation notebooks
dashboard/          # Tableau workbook(s)
reports/figures/    # exported charts
data/               # raw/processed data (ignored)
```

## Tech
Python (pandas, numpy), requests; Tableau; SQL (optional)

---
Created 2025-08-13
