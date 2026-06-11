# Publication Readiness

## Repository Status

Ready after minor housekeeping.

The repository has the core files needed for first public publication:

- Quarto website configuration
- Course Home page
- Parts I-VI
- Appendices
- Teaching dataset
- Figure assets
- Environment record
- README
- MIT License
- Changelog
- Repository structure documentation

## Render Status

Ready.

The website renders successfully from the repository root with:

```bash
quarto render
```

The generated output is:

```text
_site/index.html
```

## Website Status

Ready.

The website includes Home, Parts I-VI, and Appendices. The placeholder `notes/` folder is excluded from rendering through `_quarto.yml`.

## Dataset Status

Ready.

The preferred dataset source of truth is:

```text
data/Milk_Data_S2025n.csv
```

Duplicate active copies are present in:

- `part-iii/Milk_Data_S2025n.csv`
- `part-iv/Milk_Data_S2025n.csv`
- `part-v/Milk_Data_S2025n.csv`

Additional staging copies exist under `staging/`, which is ignored by Git.

## Documentation Status

Ready.

Publication support files are present:

- `README.md`
- `LICENSE`
- `CHANGELOG.md`
- `docs/REPOSITORY_STRUCTURE.md`
- `docs/PUBLICATION_READY.md`

## Recommended Next Step

The repository is ready for a local commit after reviewing the generated file list.

For GitHub upload, keep the source files, data, figures, appendices, `_quarto.yml`, `_environment`, and documentation files. Development-only folders such as `staging/`, `incoming-zips/`, `.venv/`, `.quarto/`, and `_site/` are ignored by Git.

For GitHub Pages publication, use a Quarto GitHub Pages workflow or another deployment method that renders the site and publishes `_site/`.
