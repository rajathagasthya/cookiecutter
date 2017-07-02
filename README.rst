===============
py-cookiecutter
===============

Cookiecutter template for a Python project. See https://github.com/audreyr/cookiecutter.

This is based on (and forked from) the OpenStack cookiecutter template at
`openstack-dev/cookiecutter`_ to use ``pbr``, and uses ``pytest`` instead of
OpenStack's ``testrepository`` for running tests. However, this cookiecutter
template is for generic use and is not OpenStack specific.

* Free software: MIT license
* pbr_: Set up to use Python Build Reasonableness
* hacking_: Enforces the OpenStack Hacking Guidelines
* pytest_: Supports unittest, pytest, nose style tests and more
* Tox_ testing: Setup to easily test for Python 2.7, 3.5, 3.6
* Sphinx_ docs: Documentation ready for generation and publication

Usage
-----

Install cookiecutter::

    pip install cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/rajathagasthya/py-cookiecutter.git

.. _pbr: http://docs.openstack.org/developer/pbr
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _hacking: https://git.openstack.org/cgit/openstack-dev/hacking/plain/HACKING.rst
.. _pytest: http://pytest.org/
.. _openstack-dev/cookiecutter: https://github.com/openstack-dev/cookiecutter
