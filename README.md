# self_investment

<p align="center">
<a href="https://pypi.python.org/pypi/mlops_structure">
    <img src="https://img.shields.io/pypi/v/mlops_structure.svg"
        alt = "Release Status">
</a>
<a href="https://pehls.github.io/mlops_structure/">
    <img src="https://img.shields.io/website/https/pehls.github.io/mlops_structure/index.html.svg?label=docs&down_message=unavailable&up_message=available" alt="Documentation Status">
</a>
<a href="https://pehls.github.io/mlops_structure/tests/coverage">
    <img src="./docs/badges/coverage-badge.svg" alt="Test Coverage">
</a>
</a>
<a href="https://pehls.github.io/mlops_structure/tests/report">
    <img src="./docs/badges/tests-badge.svg" alt="Tests">
</a>
</p>

## Project Organization

```
│
├── descriptive        <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `_` delimited description, e.g.
│                         `01_gtrp_initial_data_exploration`.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   │
│   └── figures        <- Generated graphics and figures to be used in reporting
│   │
│   └── pages          <- Pages containing code to generate streamlit dash
│   │   │ 
│   │   └── xxx.py        <- Presentation about model development
│   │
│   └── Análise.py      <- Main page of the report
│
├── self_investment    <- Package with all content
│   │
│   └── docs        <- A default mkdocs project; see www.mkdocs.org for details
│   │   │ 
│   │   └── badges      <- base png to be used to generate the coverage and test quants
│   │   │ 
│   │   └── tests       <- additional sources to generate pytest report
│
├── poetry.lock     <- poetry lock file to generate specific environment
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         self_investment and configuration for tools like black
│
├── README.md         <- readme markdown file to git
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
```

--------

* Documentation: <https://pehls.github.io/self_investment/>

# Venv
to activate, in a windows terminal, inside `self_investment` folder, put `.venv\Scripts\activate`