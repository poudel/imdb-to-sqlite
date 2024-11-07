# imdb-to-sqlite

[![PyPI](https://img.shields.io/pypi/v/imdb-to-sqlite.svg)](https://pypi.org/project/imdb-to-sqlite/)
[![Changelog](https://img.shields.io/github/v/release/poudel/imdb-to-sqlite?include_prereleases&label=changelog)](https://github.com/poudel/imdb-to-sqlite/releases)
[![Tests](https://github.com/poudel/imdb-to-sqlite/actions/workflows/test.yml/badge.svg)](https://github.com/poudel/imdb-to-sqlite/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/poudel/imdb-to-sqlite/blob/master/LICENSE)

IMDB non-commercial data as sqlite database

## Installation

Install this tool using `pip`:
```bash
pip install imdb-to-sqlite
```
## Usage

For help, run:
```bash
imdb-to-sqlite --help
```
You can also use:
```bash
python -m imdb_to_sqlite --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd imdb-to-sqlite
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
