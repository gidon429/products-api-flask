# Contributor's Guide

## Prerequisites

Install Python 3.6 and Pip and Pipenv.

## Installation

Download source code:

```sh
git clone git@github.com:s2t2/products-api-flask.git
cd products-api-flask/
```

Install package dependencies, including Flask:

```sh
pipenv install
```

## Usage

All following commands assume you are running them from within a Pipenv virtual environment:

```sh
pipenv shell
```

Start a local webserver:

```sh
flask run
```