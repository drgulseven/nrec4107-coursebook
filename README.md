# NREC4107 Applied Intermediate Econometrics

## Overview

This repository contains a Quarto-based coursebook for NREC4107 Applied Intermediate Econometrics at Sultan Qaboos University.

The coursebook focuses on:

- data analysis
- visualization
- regression
- econometric diagnostics
- machine learning basics
- empirical project writing

using Python.

## Course Structure

| Part | Focus |
|---|---|
| Part I. Data and Python | Data foundations, Python workflow, and data cleaning |
| Part II. Visualization | Descriptive statistics and exploratory graphs |
| Part III. Regression | OLS regression, inference, functional forms, and model selection |
| Part IV. Econometric Problems | Heteroskedasticity, autocorrelation, multicollinearity, endogeneity, and diagnostics |
| Part V. Machine Learning | Prediction, train-test splits, trees, random forests, boosting, and feature importance |
| Part VI. Empirical Project | Research questions, data sections, methodology, results, and final project writing |
| Appendices | Formula sheet, Python code guide, exam practice, project checklist, and dataset integrity |

## Software

The coursebook uses:

- Quarto
- Python
- Jupyter
- Pandas
- Statsmodels
- Scikit-learn

## Dataset

The main teaching dataset is `Milk_Data_S2025n.csv`. It is used to demonstrate data cleaning, visualization, regression, diagnostics, prediction, and project writing. Some chapters also discuss broader agricultural and natural resource economics applications.

## Rendering

Render the full website from the repository root:

```bash
quarto render
```

Preview the website locally:

```bash
quarto preview
```

## Repository Structure

- `part-i/` through `part-vi/`: coursebook parts and chapters
- `appendices/`: student reference appendices
- `data/`: teaching dataset
- `figures/`: shared figure assets
- `_quarto.yml`: Quarto website configuration
- `_environment`: environment record for reproducible rendering
- `_site/`: generated website output after rendering
- `docs/`: repository reports and documentation

## License

This project is released under the MIT License. See `LICENSE` for details.
