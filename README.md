Metagenesys
===========

Take the information from a Python `setup.cfg` file and generate a `codemeta.json` file.

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg?style=flat-square)](https://choosealicense.com/licenses/bsd-3-clause)
[![Latest release](https://img.shields.io/github/v/release/caltechlibrary/metagenesys.svg?style=flat-square&color=b44e88)](https://github.com/caltechlibrary/metagenesys/releases)


Table of contents
-----------------

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
* [Known issues and limitations](#known-issues-and-limitations)
* [Getting help](#getting-help)
* [Contributing](#contributing)
* [License](#license)
* [Authors and history](#authors-and-history)
* [Acknowledgments](#authors-and-acknowledgments)


Introduction
------------

The goal of [CodeMeta](https://codemeta.github.io) is to create a concept vocabulary that can be used to standardize the exchange of software metadata across repositories and organizations.  A _CodeMeta instance file_ (named [`codemeta.json`](https://codemeta.github.io/user-guide/) by convention) describes the metadata associated with a software object using JSON's linked data ([JSON-LD](https://json-ld.org)) notation, with a [standardized set of terms](https://codemeta.github.io/terms/).  Currently, software authors have to write `codemeta.json` files by hand or use tools such as the [CodeMeta generator](https://codemeta.github.io/codemeta-generator/).

Python developers frequently use [setuptools](https://pypi.org/project/setuptools/) to configure their software in a reproducible manner, and in 2016, [setuptools version 30.3.0](https://setuptools.readthedocs.io/en/latest/history.html#v30-3-0) introduced a declarative file format, [`setup.cfg`](https://setuptools.readthedocs.io/en/latest/setuptools.html#configuring-setup-using-setup-cfg-files), where authors can put configuration information that previously went into `setup.py` files.  A glance at `setup.cfg` files shows that the information contained in them includes some of the same information that is needed by `codemeta.json` files.
 
Metagenesys ("_**Meta**data **gene**rator u**s**ing P**y**thon **s**etup.cfg_") is a program to create and keep in sync a `codemeta.json` file from a Python package's `setup.cfg` file.


Installation
------------

_Forthcoming ..._
 

Usage
-----

_Forthcoming ..._

Known issues and limitations
----------------------------

_Forthcoming ..._


Getting help
------------

_Forthcoming ..._


Contributing
------------

_Forthcoming ..._


License
-------

Software produced by the Caltech Library is Copyright (C) 2020, Caltech.  This software is freely distributed under a BSD/MIT type license.  Please see the [LICENSE](LICENSE) file for more information.


Authors and history
---------------------------


Acknowledgments
---------------

This work was funded by the California Institute of Technology Library.

<div align="center">
  <br>
  <a href="https://www.caltech.edu">
    <img width="100" height="100" src=".graphics/caltech-round.svg">
  </a>
</div>
