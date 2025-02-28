# fors2pcigale

[![Template](https://img.shields.io/badge/Template-LINCC%20Frameworks%20Python%20Project%20Template-brightgreen)](https://lincc-ppt.readthedocs.io/en/latest/)

[![PyPI](https://img.shields.io/pypi/v/fors2pcigale?color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/fors2pcigale/)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/sylvielsstfr/fors2pcigale/smoke-test.yml)](https://github.com/sylvielsstfr/fors2pcigale/actions/workflows/smoke-test.yml)
[![codecov](https://codecov.io/gh/sylvielsstfr/fors2pcigale/branch/main/graph/badge.svg)](https://codecov.io/gh/sylvielsstfr/fors2pcigale)
[![Read the Docs](https://img.shields.io/readthedocs/fors2pcigale)](https://fors2pcigale.readthedocs.io/)
[![benchmarks](https://img.shields.io/github/actions/workflow/status/sylvielsstfr/fors2pcigale/asv-main.yml?label=benchmarks)](https://sylvielsstfr.github.io/fors2pcigale/)

This project was automatically generated using the LINCC-Frameworks 
[python-project-template](https://github.com/lincc-frameworks/python-project-template).

A repository badge was added to show that this project uses the python-project-template, however it's up to
you whether or not you'd like to display it!

For more information about the project template see the 
[documentation](https://lincc-ppt.readthedocs.io/en/latest/).


## Introduction


This package is dedicated to run SED fitting on Fors2 data ``CIGALE``,
which's accronym means CIGALE means **Code Investigating GALaxy Emission**.
The package implemented in python is refered as ``pcigale``.


### CIGALE code

The top page for [pcigale](https://cigale.lam.fr/).
The ``cigale`` documentation can be found at [https://cigale.lam.fr/documentation/](https://cigale.lam.fr/documentation/).

The installation of ``pcigale`` requires a python environnement with the packages:

- ``astropy numpy scipy matplotlib configobj rich``
- and for plotting in a notebook environnement :``ipykernel``, ``jupyterlab``, and ``ipympl``.


## Dev Guide - Getting Started

Before installing any dependencies or writing code, it's a great idea to create a
virtual environment. LINCC-Frameworks engineers primarily use `conda` to manage virtual
environments. If you have conda installed locally, you can run the following to
create and activate a new environment.

```
>> conda create env -n <env_name> python=3.10
>> conda activate <env_name>
```

Once you have created a new environment, you can install this project for local
development using the following commands:

```
>> pip install -e .'[dev]'
>> pre-commit install
>> conda install pandoc
```

Notes:
1) The single quotes around `'[dev]'` may not be required for your operating system.
2) `pre-commit install` will initialize pre-commit for this local repository, so
   that a set of tests will be run prior to completing a local commit. For more
   information, see the Python Project Template documentation on 
   [pre-commit](https://lincc-ppt.readthedocs.io/en/latest/practices/precommit.html)
3) Install `pandoc` allows you to verify that automatic rendering of Jupyter notebooks
   into documentation for ReadTheDocs works as expected. For more information, see
   the Python Project Template documentation on
   [Sphinx and Python Notebooks](https://lincc-ppt.readthedocs.io/en/latest/practices/sphinx.html#python-notebooks)
