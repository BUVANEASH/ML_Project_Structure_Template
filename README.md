# ML_Project_Structure_Template

## Machine Learning project structure

Based on *https://drivendata.github.io/cookiecutter-data-science/*

```
.
├── LICENSE
│
├── data
|   ├── external       <- Data from third party sources.
│   ├── raw            <- The original, immutable data dump. 
│   ├── intermediate   <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── temp           <- Temporary Data storage.
│
├── results
│   ├── outputs        <- Generated Outputs.
│   └── models         <- Trained and serialized models, model predictions, or model summaries.
│
├── documents
│   ├── docs           <- A default Sphinx project; see sphinx-doc.org for details.
│   ├── images         <- Images figures to be used in reporting.
│   └── references     <- Data dictionaries, manuals, and all other explanatory materials.
│
├── notebooks          <- notebooks for explorations / prototyping,
│						  Contains jupyter notebook demo scripts
│
├── src                <- all source code, internal org as needed,
│		                  Name src folder as "project_name"/src/scripts
│
├── Makefile           <- Makefile with commands like `make data` or `make train` / tasks
├── setup.py           <- Make this project pip installable with `pip install -e`
├── README.md          <- The top-level README for developers using this project.
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                          generated with `pip freeze > requirements.txt`
└── Dockerfile         <- Dockerfile to create docker image.
```
