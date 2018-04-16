========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/roadmap-as-code/badge/?style=flat
    :target: https://readthedocs.org/projects/roadmap-as-code
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/markuszoeller/roadmap-as-code.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/markuszoeller/roadmap-as-code

.. |requires| image:: https://requires.io/github/markuszoeller/roadmap-as-code/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/markuszoeller/roadmap-as-code/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/markuszoeller/roadmap-as-code/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/markuszoeller/roadmap-as-code

.. |version| image:: https://img.shields.io/pypi/v/roadmap-as-code.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/roadmap-as-code

.. |commits-since| image:: https://img.shields.io/github/commits-since/markuszoeller/roadmap-as-code/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/markuszoeller/roadmap-as-code/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/roadmap-as-code.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/roadmap-as-code

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/roadmap-as-code.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/roadmap-as-code

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/roadmap-as-code.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/roadmap-as-code


.. end-badges

A developer friendly way to create and maintain a roadmap for your project.

* Free software: MIT license

Installation
============

::

    pip install roadmap-as-code

Documentation
=============

https://roadmap-as-code.readthedocs.io/

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
