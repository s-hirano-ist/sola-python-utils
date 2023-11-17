# Python Utils

## 使い方

### Pyenv

```bash
which python
```

install specific version of python

```bash
pyenv install --list
pyenv install PYTHON_VERSION
```

set global python version

```bash
pyenv local PYTHON_VERSION
pyenv global PYTHON_VERSION
python --version
```

### Poetry

poetry自体のupdate

```bash
poetry self update
```

add library

```bash
poetry add LIBRARY_NAME
```

install

```bash
poetry install
```

build

```bash
poetry build
```

run

```bash
poetry run python SRC_PATH
```

update poetry lock file

```bash
poetry lock
```

## Reference

pyenv + poetry

> https://dev.classmethod.jp/articles/pyenv-and-poetry/
