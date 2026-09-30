# COVID-19 Vaccination vs Outcomes: Exploratory Analysis

Group project that explores whether countries with higher vaccination totals had fewer COVID-19 deaths, written as clean, defensive Python.

**Tools:** Python · pandas · NumPy · matplotlib · seaborn

## Highlights
- Reusable cleaning functions with **type annotations, docstrings and input/output validation**
- A **custom `DataValidationError` exception** so bad input fails clearly instead of crashing
- EDA: cases per 1M distribution, global vaccine frequency and vaccination growth by country over time
- Correlation heatmap, vaccinations vs cases/deaths, and a **hypothesis test**: *is there a negative correlation between total vaccinations and total deaths?*

## Findings
Countries with high vaccination totals tended to show lower death and case severity. The relationship isn't perfectly linear, but overall it supports the hypothesis.

## Data
`data/country_vaccinations.csv` and `data/worldometer_data.csv` (public Kaggle COVID-19 datasets).

## Run it
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook covid19_analysis.ipynb
```

## Team
Chetan Babu Mahendiran · Micheal Kennedy · David Compagno · Shahmeer Khan

---
*MSc Data Science & Analytics, Munster Technological University (Python for Data Analytics)*
