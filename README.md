# Cookiecutter Data Science

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work in both Python and R._

This is a fork of [cookiecutter-data-science](http://drivendata.github.io/cookiecutter-data-science/), updated with support for R and with some modern bells and whistles added on.

## Requirements to use the cookiecutter template

- Python 2.7 or 3.5+
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` sh
conda install -c conda-forge cookiecutter
```

or

``` sh
pip install cookiecutter
```

### Starting a new project

To start a new project, run:

```sh
cookiecutter https://github.com/royalts/cookiecutter-data-science
```

[![asciicast](https://asciinema.org/a/244658.svg)](https://asciinema.org/a/244658)

### The resulting directory structure

```sh
    ├── LICENSE
    ├── README.md                <- The top-level README for developers using this project.
    ├── data
    │   ├── processed            <- The final, canonical data sets for modeling.
    │   └── raw                  <- The original, immutable data dump.
    │
    ├── docs                     <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models                   <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks                <- Jupyter notebooks. Naming convention is a number (for ordering) and a short `_` delimited description, e.g. `1.0_initial_data_exploration`.
    │
    ├── references               <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports                  <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    ├── environment.yml          <- The environment file for reproducing the analysis environment, e.g.       generated with `conda export > environment.yml`
    │
    ├── setup.py                 <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                      <- Source code for use in this project.
    │   ├── __init__.py          <- Makes src a Python module
    │   │
    │   ├── data                 <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features             <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   └── models               <- Scripts to train models and then use trained models to make
    │       │                       predictions
    │       ├── predict_model.py
    │       └── train_model.py
    │
    ├── .pre-commit-config.yaml  <- [pre-commit](https://pre-commit.com/) config
    │
    └── pyproject.toml           <- Python project settings
```

## Contributing

Contributions welcome! Just [file an issue or submit a pull request](https://github.com/RoyalTS/cookiecutter-data-science/).
