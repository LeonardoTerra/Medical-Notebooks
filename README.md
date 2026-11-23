# Medical EDAs

A collection of Jupyter notebooks with **Exploratory Data Analyses (EDA)** of medical and healthcare datasets.

Each notebook explores a dataset end to end: understanding its structure, cleaning it, summarizing it with statistics and visualizations, and pulling out insights that can guide further analysis or modeling.

## Repository structure

```
Medical-EDAs/
├── notebooks/      # One notebook (or folder) per dataset / analysis
├── data/           # Small sample datasets or download instructions (raw data is not committed)
├── requirements.txt
└── README.md
```

## Notebooks

| # | Notebook | Dataset | Topics |
|---|----------|---------|--------|
| — | *Coming soon* | | |

> Add a row to this table each time a new notebook is published.

## Typical EDA workflow

1. **Data overview** – shape, data types, sample records
2. **Data quality** – missing values, duplicates, outliers, inconsistent categories
3. **Univariate analysis** – distributions of each variable
4. **Bivariate / multivariate analysis** – correlations and relationships with the outcome of interest
5. **Insights** – key findings and next steps

## Getting started

```bash
git clone https://github.com/LeonardoTerra/Medical-EDAs.git
cd Medical-EDAs
python -m venv .venv
# Windows: .venv\Scripts\activate   |   macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn · Jupyter

## Data & privacy

Only public, de-identified datasets are used. Each notebook cites its data source and license. No protected health information (PHI) is stored in this repository.

## Disclaimer

These analyses are for educational and exploratory purposes only and are **not** medical advice.

## Author

**Leonardo Terra** – [GitHub](https://github.com/LeonardoTerra)
