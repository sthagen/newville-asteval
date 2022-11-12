====================================
Downloading and Installation
====================================

.. _numpy: http://docs.scipy.org/doc/numpy
.. _github:  http://github.com/newville/asteval
.. _PyPI:  http://pypi.python.org/pypi/asteval/

Requirements
~~~~~~~~~~~~~~~

Asteval is a pure Python module with very few dependencies.  For Python 3.8 and
higher, there are no required dependencies outside of the standard
library. Python 3.7 does require the `importlib_metadata` package.  If
available, Asteval will make use of the `numpy`_ module.  The test suite
requires the `pytest` and `coverage modules, and building the documentation
requires the `sphinx` package.

The latest stable version of asteval is |release|.

Versions 0.9.28 and later support and are tested with Python 3.7 through
3.11. There are no immediate plans to drop support Python 3.7.  Python versions
have generally been supported until they are past the end-of-maintenance period
for security fixes.  Supporting new versions of the Python 3 series is
generally not too much work, but may not be guaranteed until after release of
that version.

The last version of asteval to support Python 2.7 was version 0.9.17.

Download and Installation
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The latest stable version of asteval is |release| and is available at
`PyPI`_ or as a conda package.  You should be able to install asteval
with::

   pip install asteval

It may also be available on some conda channels, including `conda-forge`,
but as it is a pure Python package with no dependencies or OS-specific
extensions, using `pip` should be the preferred method on all platforms and
environments.

Development Version
~~~~~~~~~~~~~~~~~~~~~~~~

The latest development version can be found at the `github`_ repository, and cloned with::

    git clone http://github.com/newville/asteval.git


Installation
~~~~~~~~~~~~~~~~~

Installation from source on any platform is::

   pip install .

License
~~~~~~~~~~~~~

The ASTEVAL code is distribution under the following license:

.. literalinclude:: ../LICENSE
