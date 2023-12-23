{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    |
    ├── logs               <- Implement a logging system for the agent and code
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── nlca/              <- Scripts to handle autonomous agent behaviors and interfaces with microservices
    │   ├── database_interface.py
    │   │
    │   ├── inner_loop/    <- Meditation, contemplation, inner monologue, dreams, and diaries like behaviors,
    |   |                     heavy lifting of thinking and planning
    │   │   ├── __init__.py
    │   │   ├── search.py
    │   │   ├── kernel.py
    │   │   └── dossier.py
    │   │
    │   └── outer_loop/     <- Behavioral loop of NLCA. It is responsible for handling incoming information from the outside world,  
    |       |                  compiling thoughts and decisions, and generating a response to the outside world
    │       ├── __init__.py
    │       ├── context.py
    │       ├── corpus.py
    │       ├── output.py
    │       └── environment.py
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    └──  src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── experiments    <- Scripts to manage different experiments or hyperparameter tuning configurations.
        │   └── experiment_runner.py
        |
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── tests          <- Tests for your modules and functions
        │   └── test_your_module.py
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
            └── visualize.py


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a> and the theory of <a target="_blank" href="https://www.youtube.com/@DaveShap">David Shapiro</a> about autonomous agents like <a target="_blank" href="https://github.com/daveshap/NaturalLanguageCognitiveArchitecture">Natural Lenguague Cognitive Architecture</a> and <a target="_blank" href="https://github.com/daveshap/BenevolentByDesign">Benevolent by design</a> </small></p>
