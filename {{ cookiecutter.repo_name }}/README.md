# {{cookiecutter.project_name}}

{{cookiecutter.description}}

## Project Organization

```
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

## Setup

```sh
conda env create -f environment.yml
pip install -e .
```

```sh
pre-commit install
```

## Acknowledgements

Project based on a [fork](https://github.com/RoyalTS/cookiecutter-data-science) of the [cookiecutter data science project template](https://drivendata.github.io/cookiecutter-data-science/).
