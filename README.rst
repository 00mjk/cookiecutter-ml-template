=============================
Cookiecutter Machine Learning
=============================

This template modifies the (PyPackage)[https://github.com/audreyr/cookiecutter-pypackage/] template from @audreyr.
It is modified for Machine Learning projects with CI testing (travis, tox and pytest) and documentation using sphinx. 

Cookiecutter_ template for a Python package.

* Free software: BSD license

Table Of Contents
-----------------




TODO
----

* post hook sphinx-quickstart
* travis config for docs to gh_pages
* configure pytest with pytest.ini
* configure tox.ini to make use of pipenv
* configure travis.yml to use tox
* replace pip and requirements.txt files with pipenv and Pipfile

Features
--------

* Testing setup with ``py.test``
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.7, 3.4, 3.5, 3.6
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Bumpversion_: Pre-configured version bumping with a single command
* Auto-release to PyPI_ when you push a new tag to master (optional)
* Command line interface using Click (optional)

.. _Cookiecutter: https://github.com/audreyr/cookiecutter

Build Status
-------------

Linux:

.. image:: https://img.shields.io/travis/audreyr/cookiecutter-pypackage.svg
    :target: https://travis-ci.org/audreyr/cookiecutter-pypackage
    :alt: Linux build status on Travis CI


Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis-CI_ account.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Register_ your project with PyPI.
* Run the Travis CLI command `travis encrypt --add deploy.password` to encrypt your PyPI password in Travis config
  and activate automated deployment on PyPI when you push a new tag to master branch.
* Add the repo to your ReadTheDocs_ account + turn on the ReadTheDocs service hook.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.
* Activate your project on `pyup.io`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files
.. _Register: https://packaging.python.org/distributing/#register-your-project

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

Not Exactly What You Want?
--------------------------

Don't worry, you have options:

Similar Project Skeletons
~~~~~~~~~~~~~~~~~~~~~~~~~

* `victoresque/pytorch-template`_: template for pytorch projects.

* `tdeboissiere/cookiecutter-deeplearning`_: template for deeplearning project

* `drivendata/cookiecutter-data-science`_: template for data science

* `makcedward/ds_project_template`_: data science project template

* Also see the `network`_ and `family tree`_ for this repo. (If you find
  anything that should be listed here, please add it and send a pull request!)


  
Support The CookieCutter Project
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can take our detailed course that covers all the features of this template, which has the added bonus of funding this project:

.. image:: https://www.pydanny.com/static/packaging-course.jpg
   :name: Creating and Distributing Python Packages image
   :align: center
   :alt: Creating and Distributing Python Packages
   :target: https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es

También disponible en español:

.. image:: https://www.pydanny.com/static/packaging-course-es.jpg
   :name: Creating and Distributing Python Packages ES image
   :align: center
   :alt: Creating and Distributing Python Packages ES
   :target: https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es

Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

Pull requests are welcome, if they're small, atomic, and if they
make my own packaging experience better.

Built With
~~~~~~~~~~

Credits
~~~~~~~



.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.io/
.. _`pyup.io`: https://pyup.io/
.. _Bumpversion: https://github.com/peritus/bumpversion
.. _Punch: https://github.com/lgiordani/punch
.. _PyPi: https://pypi.python.org/pypi



.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _`lgiordani/cookiecutter-pypackage`: https://github.com/lgiordani/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
