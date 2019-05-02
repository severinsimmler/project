# A generic Python project template
[![Build Status](https://travis-ci.com/severinsimmler/project.svg?branch=master)](https://travis-ci.com/severinsimmler/project)

This is a generic template for a new Python project.


## Installation
```
$ pip install project
```


## Example
```python
>>> import project
>>> project.process("example")
"example"
```


## Developing
[Pipenv](https://pipenv.readthedocs.io/en/latest/) automatically creates and manages a virtual environment, [Poetry](https://poetry.eustace.io/) builds and uploads the project to [PyPI](https://pypi.org/) – instead of letting both tools [war on each other](https://frostming.com/2018/05-15/pipenv-vs-poetry), you should use the best of both.

Install dependencies with:
```
$ pipenv install --dev
```

run tests:
```
$ pipenv run tests
```

build project:
```
$ poetry build
```

and upload it to [PyPI](https://pypi.org/):
```
$ poetry upload
```

> Save your credentials with `poetry config http-basic.pypi username password`.
