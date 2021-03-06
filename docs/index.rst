USGS Data Tools Python Package
======================================

A python package to assist with data management best practices. Currently it supports functionality with the USGS Digital Object Identifier Tool but will soon expand to more tools.

=================
Quick Start
=================

Install python requirements

``pip install -r requirements.txt``

Install usgs_datatools (locally for now)

Clone or download this package and change directory into the top level

``pip install .``

=================
Examples
=================

Please see the examples/notebook directory for a sample of DOI Tool usage (querying, creating, modifying).

Datacite queries can be ran using the new ``doi.datacite_search(10.5066/xxxxx)`` method.

=================
Contributions
=================

All kinds of contributions are greatly appreciated, please see the CONTRIBUTING.rst file for more information link

=================
Testing
=================

Testing is setup using pytest and can be started using the command below.

``python -m pytest tests/``

=================
Development
=================

Update versions

``bumpversion  --current-version 0.2.0 minor --allow-dirty``

=================
Credits
=================

Python, Requests, BeautifulSoup, PyYaml, Cookiecutter: cookiecutter, audreyr/cookiecutter-pypackage, PyTest

=================
Disclaimer
=================

Provisional Software Disclaimer Under USGS Software Release Policy, the software codes here are considered preliminary, not released officially, and posted to this repo for informal sharing among colleagues.

This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the software.

=================
Contents:
=================

.. toctree::
   :maxdepth: 2

   readme
   installation
   usage
   modules
   contributing
   authors
   history

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
