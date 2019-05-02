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
[Poetry](https://poetry.eustace.io/) automatically creates a virtual environment, builds and uploads the project to [PyPI](https://pypi.org/). Install dependencies with:
```
$ poetry install
```

build the project:
```
$ poetry build
```

and upload it to [PyPI](https://pypi.org/):
```
$ poetry upload
```

> Save your credentials with `poetry config http-basic.pypi username password`.
