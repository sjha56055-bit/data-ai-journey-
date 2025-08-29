# data-ai-journey

First steps in data/AI using Jupyter Notebook: load a CSV, handle missing values, and draw three charts. This repo contains `notebooks/01_first_notebook.ipynb` and a `data/` folder with the dataset. [1][3]

## What this notebook does
- Loads `data/sample.csv` into pandas and shows `head()`, `info()`, and `describe()` for a quick overview. [1]
- Cleans missing data: drops columns with >60% missing and imputes numeric with median, categorical with mode. [5]
- Creates three visuals: one histogram (numeric), one bar chart (categorical top 10), and one correlation heatmap (numeric). [1][5]

## How to run (Windows/macOS/Linux)
1. Install Python and Jupyter:  
python -m pip install --upgrade pip
python -m pip install notebook pandas matplotlib seaborn
Launch with:
This is the simplest beginner setup. [6][7]
2. Folder layout:
data-ai-journey/
data/ sample.csv
notebooks/ 01_first_notebook.ipynb
README.md
Put the CSV at `data/sample.csv`. [1]
3. Open the notebook from Jupyter and run cells with Shift+Enter in order. [1]

## Dataset
- Use a small starter CSV (e.g., Titanic train.csv or Iris), save it as `data/sample.csv` to match the notebook path. [8][9]

## Troubleshooting
- FileNotFoundError: ensure the notebook is inside `notebooks` and the CSV path `../data/sample.csv` is correct relative to the notebook. [5][2]
- To share publicly, create a GitHub repo and upload `notebooks/` and `README.md` via the web Upload flow. [3][4]
