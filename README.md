# Minor_project_2
# SpendDNA — Rahul Sharma's Wallet, Decoded

The Unlox Academy — Week 2 Industry-Graded Minor Project.
A Python analytics pipeline that parses 6 months of messy synthetic UPI/bank
transactions, extracts canonical vendors from inconsistent descriptions,
categorises spend across 12 categories, detects spending archetypes, flags
anomalies with a hand-built z-score, and prints a Spotify-Wrapped-style report.

## What's in this repo
- `SpendDNA_SheikAbdulSamad.ipynb` — the notebook, runs end-to-end top to bottom
- `DADS_MP2_Dataset.csv` — the provided synthetic dataset
- `README.md` — this file

## Constraints
**Allowed:** Python fundamentals, NumPy, Pandas (`read_csv`, `.dt`, `.str`, `groupby`,
`pivot_table`, `transform`, `.apply`), `pd.to_datetime`/`datetime.strptime`.

**Forbidden (and not used):** regex, `matplotlib`/`seaborn`/`plotly`,
`scikit-learn`/`scipy.stats`/`statsmodels`, `collections.Counter`,
`pandas-profiling`/`ydata-profiling`/`sweetviz`, any external dataset.

## How to run
1. Open `SpendDNA_SheikAbdulSamad.ipynb` in Google Colab or Jupyter.
2. Upload `DADS_MP2_Dataset.csv` to the same session/folder.
3. Run all cells top to bottom.

## Output
![SpendDNA Report Output](IMG_1053.png)

