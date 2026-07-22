# Exploring NYC Public School Test Results

An exploratory analysis of standardized test performance across New York City public schools. The notebook identifies high-performing mathematics schools, ranks schools by combined SAT results, and compares score variability by borough.

## Analysis questions

- Which schools meet the high-performance threshold for mathematics?
- Which schools have the strongest combined SAT scores?
- Which borough has the greatest variation in combined SAT performance?

## Tools

- Python
- pandas and NumPy
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — filtering, aggregation, ranking, and statistical summaries
- `schools.csv` — school performance data
- `schoolbus.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates conditional filtering, derived metrics, ranking, grouping, and descriptive statistics with pandas.
