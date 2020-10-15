# Duolingo API for Python

[![Build Status](https://travis-ci.org/KartikTalwar/Duolingo.svg?branch=master)](https://travis-ci.org/KartikTalwar/Duolingo)
[![Coverage Status](https://coveralls.io/repos/github/KartikTalwar/Duolingo/badge.svg?branch=master)](https://coveralls.io/github/KartikTalwar/Duolingo?branch=master)
[![PyPI version fury.io](https://badge.fury.io/py/duolingo-api.svg)](https://pypi.python.org/pypi/duolingo-api/)

Unofficial Duolingo API Written in Python. This is mostly a collection of functions that give you common data directly from the API resource dictionary. More methods to come.

##### TODO

- Integrate authenticated data

### Installation

```sh
$ pip install duolingo-api
```

### Usage

```py
import duolingo
lingo  = duolingo.Duolingo('kartik', 'my password')
```
Note: You are now required to provide a password to get any data from the Duolingo API

### Documentation
[Duolingo API for Python](DOCUMENTATION.md)
