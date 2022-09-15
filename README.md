# ComPWA demo for PyHEP 2022

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ComPWA/PyHEP2022/0.2?urlpath=%2Fnotebooks%2Ftalk.ipynb)
[![Slides](https://img.shields.io/badge/view-slides-9cf?style=flat&logo=googledrive)](https://docs.google.com/presentation/d/e/2PACX-1vRF-EG2B6u8a6Wb3--TY37bBEgM0bIxgNkCesokrTEwdQZbMwONMXOKqn5GZSirAIH9NXVv6v0ym_es/pub)
[![10.5281/zenodo.7078981](https://zenodo.org/badge/536550527.svg)](https://doi.org/10.5281/zenodo.7078981)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

This repository was prepared for [this notebook talk](https://indico.cern.ch/event/1150631/contributions/5002013) at the [PyHEP 2022 Workshop](https://indico.cern.ch/event/1150631). The accompanying slides can be viewed [here](https://docs.google.com/presentation/d/e/2PACX-1vRF-EG2B6u8a6Wb3--TY37bBEgM0bIxgNkCesokrTEwdQZbMwONMXOKqn5GZSirAIH9NXVv6v0ym_es/pub).

Beside the main [`talk.ipynb`](./talk.ipynb), there are more extensive example notebooks with some fun animations under [`extra`](./extra/):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ComPWA/PyHEP2022/main?labpath=extra%2Fintro.ipynb) [`intro.ipynb`](./extra/intro.ipynb)<br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ComPWA/PyHEP2022/main?labpath=extra%2Ffit.ipynb) [`fit.ipynb`](./extra/fit.ipynb)<br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ComPWA/PyHEP2022/main?labpath=extra%2Fpwa.ipynb) [`pwa.ipynb`](./extra/pwa.ipynb)

## Local installation

To view and run this notebook, install the PyPI packages listed under [`binder/requirements.in`](./binder/requirements.in) (the dependencies have been [pinned](https://compwa-org.readthedocs.io/develop.html#pinning-dependency-versions) for Python 3.8 in [`binder/requirements.txt`](./binder/requirements.txt)).

To develop the notebook for this talk, you require a few additional dependencies. They are defined through [`requirements.in`](./requirements.in).

It's easiest to work with [Conda](https://docs.conda.io/en/latest/index.html) ([Miniconda](https://docs.conda.io/en/latest/miniconda.html)). The installation procedure then simply becomes:

```shell
conda env create
conda activate compwa-pyhep-2022
pre-commit install
```
