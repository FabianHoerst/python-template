[![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Flake8 Status](./reports/flake8/flake8-badge.svg?dummy=8484744)](./reports/flake8/index.html)
![Repo Size](https://img.shields.io/github/repo-size/FabianHoerst/python-template)


# python-template
Python Template with some initial setups for code style and linting, as well as pre-commit checks. Flake8 is deactivated by default.


## Setup
1.) Install all requirements initially from requirements file: `pip install -r requirements.txt`

2.) Change Size badge by adjusting repo path from badge: `https://img.shields.io/github/repo-size/FabianHoerst/python-template`to `https://img.shields.io/github/repo-size/YourName/RepoName`

3.) Exchange Python badge with your version

## Setup pre commits
1.) Install with: `pre-commit install`

## Setup flake8 reports and badges
Run `make generate_badge` for generating report and badge. For help, see `make`. For checking before commiting, run `make check_all`.
