# FinSight AI

An organized workspace for financial data exploration and analysis.

## Project status

Early development. The initial notebook imports the data analysis stack; the dataset is intentionally excluded from Git because it is large and may contain sensitive transaction information.

## Repository structure

```text
finsight-ai/
├── data/
│   ├── raw/          # Local source data; not committed
│   ├── interim/      # Intermediate data; not committed
│   └── processed/    # Generated datasets; not committed
├── notebook/         # Jupyter notebooks, numbered by workflow stage
├── reports/figures/  # Generated visualizations; not committed
├── .gitignore
└── requirements.txt
```

## Setup

1. Open this repository in VS Code.
2. Create and select a Python 3.13 environment for the workspace.
3. Install dependencies from `requirements.txt` in that environment.
4. Open `notebook/01_data_exploration.ipynb` and select the workspace environment's Python kernel.
5. Run the import cell to verify the environment.

## Data handling

Place authorized source files in `data/raw/`. Data files are ignored by Git; do not commit private, regulated, or personally identifiable financial data. Keep reproducible transformations and analysis code in version control instead.
