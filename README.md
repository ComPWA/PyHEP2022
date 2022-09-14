# ComPWA demo for PyHEP 2022

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ComPWA/PyHEP2022/0.1?urlpath=%2Fnotebooks%2Ftalk.ipynb)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Local installation

A few additional dependencies are required to develop the notebook for this talk. They are defined through [`environment.yml`](./environment.yml).

It's easiest to work with [Conda](https://docs.conda.io/en/latest/index.html) ([Miniconda](https://docs.conda.io/en/latest/miniconda.html)). The installation procedure then simply becomes:

```shell
conda env create
conda activate compwa-pyhep-2022
pre-commit install
```
