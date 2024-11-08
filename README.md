> [!NOTE]  
> Forked via pypi from https://pypi.org/project/pytest-codeowners/
>
> I extracted this from their pip package because I can't get to the git repo
> (<https://github.com/Iress/pytest-codeowners>). Apparently they have a policy
> in their github org that blocks all US IPs?

# pytest-codeowners

Pytest plugin for selecting tests by GitHub CODEOWNERS.

## Quickstart

Install with:

```shell
pip install pytest-codeowners
```

## Usage

Like so:

```shell
pytest --codeowners-file docs/CODEOWNERS \
  --codeowners-owner @org/team-name \
  --codeowners-owner my@email.com \
  --codeowners-owner @MyUsername
```

## Building

To build this library as a wheel:

```sh
python setup.py bdist_wheel --universal
```

## Testing

First, make sure you install the package:

```sh
python setup.py install
```

To run all tests, simply do:

```sh
pytest
```

## Legal

Copyright 2022 [IRESS Ltd](https://www.iress.com/).

License: Apache License 2.0.
