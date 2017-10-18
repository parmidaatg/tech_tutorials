========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |coveralls|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/tech_tutorials/badge/?style=flat
    :target: https://readthedocs.org/projects/tech_tutorials
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/parmi.atg/tech_tutorials.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/parmi.atg/tech_tutorials

.. |coveralls| image:: https://coveralls.io/repos/parmi.atg/tech_tutorials/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/parmi.atg/tech_tutorials

.. |version| image:: https://img.shields.io/pypi/v/tech-tutorials.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/tech-tutorials

.. |commits-since| image:: https://img.shields.io/github/commits-since/parmi.atg/tech_tutorials/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/parmi.atg/tech_tutorials/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/tech-tutorials.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/tech-tutorials

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/tech-tutorials.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/tech-tutorials

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/tech-tutorials.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/tech-tutorials


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install tech-tutorials

Documentation
=============

https://tech_tutorials.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
