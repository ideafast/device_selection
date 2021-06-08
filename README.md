A _exprimental_ Jupyter notebook setup for analysing and visualizing WP3 Device Selection scores.

## Setup

[Poetry](https://python-poetry.org/) is used for dependency management, so please install on your local machine. Also ensure you have Python 3.0 installed; using [pyenv](https://github.com/pyenv/pyenv) is recommended. [Pre-commmit] is used to strip out the output from the notebook before commiting to version control.

```shell
poetry install
poetry run pre-commit install
```

Place the `DeviceSelectionsScoring.xslx` document you want to use in the `/local` folder.

Enter a `poetry shell` before running `jupyter notebook` **to ensure it has access to the dependencies in the virtual env.**
```shell
poetry shell
jupyter notebook
```

All notebooks are in the `/notebooks` folder. You can also use 
