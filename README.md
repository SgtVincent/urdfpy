# Fork
This is a patch fork for compatibility with numpy >= 1.19.5
- Updated networkx dependency
- Changed np.float to np.float64

# Urdfpy

[![Build Status](https://travis-ci.org/mmatl/urdfpy.svg?branch=master)](https://travis-ci.org/mmatl/urdfpy)
[![Documentation Status](https://readthedocs.org/projects/urdfpy/badge/?version=latest)](https://urdfpy.readthedocs.io/en/latest/?badge=latest)
[![Coverage Status](https://coveralls.io/repos/github/mmatl/urdfpy/badge.svg?branch=master)](https://coveralls.io/github/mmatl/urdfpy?branch=master)
[![PyPI version](https://badge.fury.io/py/urdfpy.svg)](https://badge.fury.io/py/urdfpy)

Urdfpy is a simple and easy-to-use library for loading, manipulating, saving,
and visualizing URDF files.

Extensive API documentation is provided [here](https://urdfpy.readthedocs.io/en/latest/).

<p float="left">
  <img src="https://github.com/mmatl/urdfpy/blob/master/docs/source/_static/robotiq.gif?raw=true" alt="GIF of Viewer" width="300"/>
  <img src="https://github.com/mmatl/urdfpy/blob/master/docs/source/_static/ur5.gif?raw=true" alt="GIF of Viewer" width="300"/>
</p>

## Installation
You can install urdfpy directly from pip.

```bash
# DO NOT run pip install urdfpy, which will install the original version
cd /path/to/urdfpy
pip install -e . 
```

## User Guide
Please see the user guide [here](https://urdfpy.readthedocs.io/en/latest/examples/index.html) for
more information.
