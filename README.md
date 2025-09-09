# IAI Project Template

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![uv](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json)](https://github.com/astral-sh/uv)
[![mypy](https://img.shields.io/badge/type--checked-mypy-blue?style=flat-square&logo=python)](https://github.com/python/mypy)
![Coverage Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/vinaysetty/1cc32e6b43d911995bf07adb1cce4e89/raw/coverage.template-project.main.json)

This repository serves as a template for software projects.

## Testing and GitHub actions

Using `pre-commit` hooks, `flake8`, `black`, `mypy`, `docformatter`, `pydocstyle` and `pytest` are locally run on every commit. For more details on how to use `pre-commit` hooks see [here](https://github.com/iai-group/guidelines/tree/main/python#install-pre-commit-hooks).

Similarly, Github actions are used to run `flake8`, `black`, `mypy`, `docformatter`, `pydocstyle` and `pytest` on every push and pull request and merge to main. The `pytest` also runs coverage. GitHub actions are explained in detail [here](https://github.com/iai-group/guidelines/blob/main/github/Actions.md).

For GitHub actions/CI Setup see [here](docs/CI_setup.md)
