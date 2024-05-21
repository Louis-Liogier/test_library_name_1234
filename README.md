# test_library_name_1234

[![PyPI](https://img.shields.io/pypi/v/test_library_name_1234.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/test_library_name_1234.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/test_library_name_1234)][pypi status]
[![License](https://img.shields.io/pypi/l/test_library_name_1234)][license]

[![Read the documentation at https://test_library_name_1234.readthedocs.io/](https://img.shields.io/readthedocs/test_library_name_1234/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/Louis-Liogier/test_library_name_1234/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/Louis-Liogier/test_library_name_1234/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/test_library_name_1234/
[read the docs]: https://test_library_name_1234.readthedocs.io/
[tests]: https://github.com/Louis-Liogier/test_library_name_1234/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/Louis-Liogier/test_library_name_1234
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _liogier1234lcapython_ via [pip] from [PyPI]:

```console
$ pip install liogier1234lcapython
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_liogier1234lcapython_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://test_library_name_1234.readthedocs.io/en/latest/usage.html
[License]: https://github.com/Louis-Liogier/test_library_name_1234/blob/main/LICENSE
[Contributor Guide]: https://github.com/Louis-Liogier/test_library_name_1234/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/Louis-Liogier/test_library_name_1234/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_test_library_name_1234
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```