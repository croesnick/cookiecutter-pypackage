======================
Cookiecutter PyPackage
======================

.. image:: https://pyup.io/repos/github/croesnick/cookiecutter-pypackage/shield.svg
     :target: https://pyup.io/repos/github/croesnick/cookiecutter-pypackage/
     :alt: Updates

.. image:: https://travis-ci.org/croesnick/cookiecutter-pypackage.svg?branch=master
    :target: https://travis-ci.org/croesnick/cookiecutter-pypackage

Cookiecutter_ template for a Python package.

* GitHub repo: https://github.com/croesnick/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

* Testing setup with pytest_
* Linting with flake8_ and static code analysis with mypy_
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 3.5, 3.6, 3.7, 3.8
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* bump2version_: Pre-configured version bumping with a single command
* Auto-release to PyPI_ when you push a new tag to master (optional)
* Command line interface using Click (optional)

Build Status
-------------

Linux:

.. image:: https://img.shields.io/travis/croesnick/cookiecutter-pypackage.svg
    :target: https://travis-ci.org/croesnick/cookiecutter-pypackage
    :alt: Linux build status on Travis CI

Windows:

.. image:: https://ci.appveyor.com/api/projects/status/github/croesnick/cookiecutter-pypackage?branch=master&svg=true
    :target: https://ci.appveyor.com/project/croesnick/cookiecutter-pypackage/branch/master
    :alt: Windows build status on Appveyor

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    $ pip install -U cookiecutter

Generate a Python package project::

    $ cookiecutter https://github.com/croesnick/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis-CI_ account.
* Install the dev requirements (optional: inside a virtualenv): ``pip install -e .[dev]``
* Register_ your project with PyPI.
* Run the Travis CLI command ``travis encrypt --add deploy.password`` to encrypt your PyPI password in Travis config
  and activate automated deployment on PyPI when you push a new tag to master branch.
* Add the repo to your ReadTheDocs_ account & turn on the ReadTheDocs service hook.
* Release your package by pushing a new tag to master.
* Specify your package's requirements (with optional version pinning) inside the ``setup.py``
  (see: ``requirements`` list).
  For more info about the format of dependencies, compare `pip docs for requirements files`_.
* Activate your project on `pyup.io`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files
.. _Register: https://packaging.python.org/tutorials/packaging-projects/#uploading-the-distribution-archives

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description.

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

Or Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter

.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.io/
.. _`pyup.io`: https://pyup.io/
.. _bump2version: https://github.com/c4urself/bump2version
.. _Punch: https://github.com/lgiordani/punch
.. _Pipenv: https://pipenv.readthedocs.io/en/latest/
.. _PyPi: https://pypi.python.org/pypi
.. _flake8: http://flake8.pycqa.org/en/latest/
.. _mypy: http://mypy-lang.org/
.. _pytest: https://docs.pytest.org/en/latest/

.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _`lgiordani/cookiecutter-pypackage`: https://github.com/lgiordani/cookiecutter-pypackage
.. _`briggySmalls/cookiecutter-pypackage`: https://github.com/briggySmalls/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/croesnick:master...master
.. _`network`: https://github.com/croesnick/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/croesnick/cookiecutter-pypackage/network/members
