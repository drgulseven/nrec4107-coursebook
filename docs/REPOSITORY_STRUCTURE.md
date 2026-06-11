# Repository Structure

This document summarizes the intended structure of the NREC4107 Quarto coursebook repository for public GitHub publication.

| Folder / file | Purpose |
|---|---|
| `_quarto.yml` | Main Quarto website configuration, render list, sidebar, navbar, theme, and Python kernel setting. |
| `_environment` | Environment record kept for reproducible local rendering. |
| `index.qmd` | Course Home page. |
| `part-i/` | Part I chapters on data foundations, Python, and cleaning. |
| `part-ii/` | Part II chapters on descriptive statistics and visualization. |
| `part-iii/` | Part III chapters on regression, inference, functional forms, dummy variables, and model selection. |
| `part-iv/` | Part IV chapters on econometric problems and diagnostics. |
| `part-v/` | Part V chapters on prediction and machine learning extensions. |
| `part-vi/` | Part VI chapters on the empirical project. |
| `appendices/` | Formula sheet, Python code guide, exam practice, project checklist, and dataset integrity appendix. |
| `data/` | Shared teaching dataset. The preferred source of truth is `data/Milk_Data_S2025n.csv`. |
| `figures/` | Shared figure assets used by the website. |
| `docs/` | Repository review reports and publication documentation. |
| `_freeze/` | Quarto freeze artifacts used by the current render workflow. |
| `_site/` | Generated website output after `quarto render`. This is ignored by Git and can be regenerated. |
| `.venv/` | Local Python virtual environment. This is ignored by Git. |
| `.quarto/` | Local Quarto cache and project state. This is ignored by Git. |
| `staging/` | Development package extraction area. Not intended for publication. Ignored by Git. |
| `incoming-zips/` | Original incoming package zip files. Not intended for publication. Ignored by Git. |
| `notes/` | Excluded placeholder notes folder. It is not rendered because `_quarto.yml` excludes `notes/`. |

## Active Website Files

The active website source consists of:

- `_quarto.yml`
- `index.qmd`
- `part-i/*.qmd`
- `part-ii/*.qmd`
- `part-iii/*.qmd`
- `part-iv/*.qmd`
- `part-v/*.qmd`
- `part-vi/*.qmd`
- `appendices/*.qmd`
- required supporting data and figure assets

## Development-Only Material

The following folders are development artifacts and should not be uploaded as active source material:

- `staging/`
- `incoming-zips/`
- `.venv/`
- `.quarto/`
- `_site/`
- local cache folders such as `.jupyter/`, `.matplotlib/`, and `.ipynb_checkpoints/`

## Dataset Placement

The preferred source of truth is:

```text
data/Milk_Data_S2025n.csv
```

Duplicate copies currently exist in some part folders to support chapter-local execution. They should not be deleted without first checking render behavior and chapter-local execution assumptions.
