
# Cookiecutter Machine Learning

## Summary 

It is modified for Machine Learning projects
with CI testing (travis, tox and pytest) and documentation using sphinx.

Templates are processed by the 
[Cookiecutter](https://github.com/audreyr/cookiecutter) software tool.  

-   Free software: BSD license

## Table Of Contents


## Todo

-   post hook sphinx-quickstart
-   travis config for docs to gh_pages
-   configure pytest with pytest.ini
-   configure tox.ini to make use of pipenv
-   configure travis.yml to use tox
-   replace `pip` and `requirements.txt` files with `pipenv` and `Pipfile`

## Features

-   Testing setup with [py.test](https://docs.pytest.org/en/latest/)
-   [Travis-CI](http://travis-ci.org/): Ready for Travis Continuous
    Integration testing
-   [Tox](http://testrun.org/tox/) testing: Setup to easily test for
    Python versions
-   [Sphinx](http://sphinx-doc.org/) docs: Documentation ready for
    generation with, for example, [ReadTheDocs](https://readthedocs.io/)
-   [Bumpversion](https://github.com/peritus/bumpversion):
    Pre-configured version bumping with a single command
-   Auto-release to [PyPI](https://pypi.python.org/pypi) when you push a
    new tag to master (optional)
-   Command line interface using Click (optional)

## Build Status

**Linux**:

[![Linux build status on Travis CI](svg)](travis-link)

**Windows**:

Not supported.

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this
requires Cookiecutter 1.4.0 or higher):

    `pipenv install cookiecutter`

Generate a Python package project from this template:

    `cookiecutter https://github.com/project-delphi/cookiecutter-ml-template.git`

Then:

-   Create a repo and put it there.
-   Add the repo to your [Travis-CI](http://travis-ci.org/) account.
-   Install the dev requirements using `pipenv` from an `Pipfile`.
     `pipenv install`
-   [Register](https://packaging.python.org/distributing/#register-your-project)
    your project with PyPI.
-   Run the Travis CLI command travis encrypt --add deploy.password to
    encrypt your PyPI password in Travis config and activate automated
    deployment on PyPI when you push a new tag to master branch.
-   Add the repo to your [ReadTheDocs](https://readthedocs.io/)
    account + turn on the ReadTheDocs service hook.
-   Release your package by pushing a new tag to master.
-   Add a requirements.txt file that specifies the packages you will
    need for your project and their versions. For more info see the [pip
    docs for requirements
    files](https://pip.pypa.io/en/stable/user_guide/#requirements-files).
-   Activate your project on [pyup.io](https://pyup.io/).

For more details, see the [cookiecutter-pypackage
tutorial](https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html).

## Not Exactly What You Want?

Don't worry, you have options:

### Similar Projects

Related Cookiecutter Templates:

-   [pytorch-template](https://github.com/victoresque/pytorch-template) for pytorch projects
-   [deeplearning](https://github.com/tdeboissiere/cookiecutter-deeplearning): template for
    deeplearning projects
-   Driven Data's [data science](https://github.com/drivendata/cookiecutter-data-science) template 
    for data science projects

Other Project Templates Without Cookiecutter

-   [Data Science project template](https://github.com/makcedward/ds_project_template)
-   [Deep Learning project template](https://github.com/L1aoXingyu/Deep-Learning-Project-Template)
-   [Keras project template](https://github.com/Ahmkel/Keras-Project-Template) 

Also see the [network](https://github.com/project-delphi/cookiecutter-ml-template/network) and [family tree](https://github.com/project-delphi/cookiecutter-ml-template/network/dependents) for this repo. (If you find 
anything that should be listed here, please add it and send a pull request!)

### Fork This / Create Your Own

If you have differences in your preferred setup, I encourage you to fork
this to create your own version. Or create your own; it doesn't strictly
have to be a fork.

### Submit a Pull Request

Pull requests are welcome, if they're small, atomic, and if they make my
own packaging experience better.

## Support The CookieCutter Project

You can take our detailed course that covers all the features of the cookiecutter project, 
which has the added bonus of funding it:

[![Creating and Distributing Python Packages](https://www.pydanny.com/static/packaging-course.jpg)](https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es)

También disponible en español:

[![Creating and Distributing Python Packages ES](https://www.pydanny.com/static/packaging-course-es.jpg)](https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es)


## Built With

[py.test](https://www.pytest.org)
[Travis-CI](http://travis-ci.org/)
[Tox](http://testrun.org/tox/)
[Sphinx](http://sphinx-doc.org/)
[ReadTheDocs](https://readthedocs.io/)
[Bumpversion](https://github.com/peritus/bumpversion):
[PyPI](https://pypi.python.org/pypi) 
[Click](https://click.palletsprojects.com)

## Credits


This template is heavily based on [PyPackage](https://github.com/audreyr/cookiecutter-pypackage)
template from [@audreyr](https://github.com/audreyr).

It is also inspired by [Data Science](https://github.com/drivendata/cookiecutter-data-science) template from [Driven Data](https://github.com/drivendata). 