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
        | |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/gamsmosys/badge/?style=flat
    :target: https://readthedocs.org/projects/gamsmosys
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/MPavicevic/gamsmosys.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/MPavicevic/gamsmosys

.. |requires| image:: https://requires.io/github/MPavicevic/gamsmosys/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/MPavicevic/gamsmosys/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/MPavicevic/gamsmosys/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/MPavicevic/gamsmosys

.. |codeclimate| image:: https://codeclimate.com/github/MPavicevic/gamsmosys/badges/gpa.svg
   :target: https://codeclimate.com/github/MPavicevic/gamsmosys
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/gamsmosys.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/gamsmosys

.. |wheel| image:: https://img.shields.io/pypi/wheel/gamsmosys.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/gamsmosys

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/gamsmosys.svg
    :alt: Supported versions
    :target: https://pypi.org/project/gamsmosys

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/gamsmosys.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/gamsmosys

.. |commits-since| image:: https://img.shields.io/github/commits-since/MPavicevic/gamsmosys/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/MPavicevic/gamsmosys/compare/v0.0.1...master



.. end-badges

Generation of OSeMOSYS input files for GAMS

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install gamsmosys

You can also install the in-development version with::

    pip install https://github.com/MPavicevic/gamsmosys/archive/master.zip


Documentation
=============


https://gamsmosys.readthedocs.io/


Development
===========

To run all the tests run::

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
