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
[Pipenv](https://pipenv.readthedocs.io/en/latest/) automatically creates and manages a virtualenv for the dependencies. To install the project's dependencies:

```
$ pipenv install --dev
```

Build the project with [Poetry](https://poetry.eustace.io/):
```
$ poetry build
```

and upload it to [PyPI](https://pypi.org/):
```
$ poetry upload
```

> Save your credentials with `poetry config http-basic.pypi username password`.
