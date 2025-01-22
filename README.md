# COM-demo-working-project-repo README

.

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Flake8 Status](./reports/badges/flake8-badge.svg)](./reports/flake8/index.html)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![Linting: pylint](https://img.shields.io/badge/linting-pylint-yellowgreen)](https://github.com/pylint-dev/pylint)
[![Tests Status](./reports/badges/junit-tests-badge.svg)](./reports/junit/html-test-report.html)
![Tests Coverage](./reports/badges/cov-badge.svg)

---

## Version

Current version is 0.1.0 and was set according to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Project's version should be updated, when applicable:

- In this very file.
- In the changelog.
- In the \_\_init\_\_.py file inside working_project
- In the pyproject.toml file.

## Prerequisites

- [Poetry](https://github.com/python-poetry/poetry)
- [Pyenv](https://github.com/pyenv/pyenv)

## Documentation

In order to generate documentation, simply run:

```bash
poetry run pdoc -o docs -d google working_project
```

## Installation

In order to install the project, simply run:

```bash
poetry install
```

## Building

In order to generate a .whl file to distribute the project, simply run:

```bash
poetry build
```

## License

Developed by Centro Tecnolóxico de Telecomunicacións de Galicia (GRADIANT) (c) 2024

See license file for more information.

## Authors

- [Andrés Ferreiro González](aferreiro@gradiant.org)

## Maintainer

- [Andrés Ferreiro González](aferreiro@gradiant.org)
