
# Cookiecutter Machine Learning

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-science.svg)](https://forthebadge.com)

[![Linux build status on Travis CI](https://travis-ci.org/project-delphi/cookiecutter-ml-template.svg?branch=master)](https://travis-ci.org/project-delphi/cookiecutter-ml-template)

## Summary

This project is an opinionated template  for ML projects which creates package skeletons.

Once generated, the package skeletons have the following features:

-  Good base folder structure for many kinds of ML Projects
-  CI testing (travis, tox and pytest)
-  Automated building, versioning and hosting of documentation (sphinx on github pages)
- using `pipenv` and the `Pipfile` format to manage virtual environments and dependencies.

The project template is populated and then processed by the excellent [Cookiecutter](https://github.com/audreyr/cookiecutter) Python tool.  

## Table Of Contents

[TL;DR](#TLDR)

- [Todo](#Todo)
- [Features](#Features)
- [Build Status](#Build-Status)
- [Quickstart](#Quickstart)
- [Alternatives](#Alternatives)
- [Support](#Support-The-CookieCutter-Project)
- [Feedback](#Feedback)
- [Built With](#Built-With)
- [Credits](#Credits)
- [License](#License)


---


## TL;DR

The objective of this project is to provide a generic machine learning template for python based projects. This includes folder structure, testing and documentation tools integrated with travis and github which should work well for most small to midsize (in terms of number of features & examples) projects using a single instance of a machine.

---

## Todo

-   post hook sphinx-quickstart
-   travis config for docs to gh_pages

---

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

---

## Build Status

**Linux**:

[![Linux build status on Travis CI](https://travis-ci.org/project-delphi/cookiecutter-ml-template.svg?branch=master)](https://travis-ci.org/project-delphi/cookiecutter-ml-template)

**Windows**:

Not supported for now.

---

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this
requires Cookiecutter 1.4.0 or higher):

    pipenv install cookiecutter

Generate a Python package project from this template:

    cookiecutter https://github.com/project-delphi/cookiecutter-ml-template.git

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

---

## Alternatives

Not Exactly What You Want? Don't worry, you have options. You can look at:

- Similar Projects
    - Other Cookiecutter Templates
    - Non Cookiecutter Package Skeletons
- Fork this project
- Submit a Pull Request

---

### Similar Projects

Related Cookiecutter Templates:

-   [pytorch-template](https://github.com/victoresque/pytorch-template) for pytorch projects
-   [deeplearning](https://github.com/tdeboissiere/cookiecutter-deeplearning): template for
    deeplearning projects
-   [Driven Data](http://drivendata.github.io/cookiecutter-data-science/)'s [data science](https://github.com/drivendata/cookiecutter-data-science) template 
    for data science projects

Other Project Templates Without Cookiecutter

-   [Data Science project template](https://github.com/makcedward/ds_project_template)
-   [Deep Learning project template](https://github.com/L1aoXingyu/Deep-Learning-Project-Template)
-   [Keras project template](https://github.com/Ahmkel/Keras-Project-Template) 

Also see the [network](https://github.com/project-delphi/cookiecutter-ml-template/network) and [family tree](https://github.com/project-delphi/cookiecutter-ml-template/network/dependents) for this repo. (If you find 
anything that should be listed here, please add it and send a pull request!)

---

### Fork This / Create Your Own

If you have differences in your preferred setup, I encourage you to fork
this to create your own version. Or create your own; it doesn't strictly
have to be a fork.

---

### Submit a Pull Request

Pull requests are welcome, if they're small, atomic, and if they make my
own packaging experience better.

---

## Feedback

Aside from PR's you can contact me on [twitter](https://twitter.com/ravkalia1).

---

## Support The CookieCutter Project

You can take our detailed course that covers all the features of the cookiecutter project, 
which has the added bonus of funding it:

[![Creating and Distributing Python Packages](https://www.pydanny.com/static/packaging-course.jpg)](https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es)

También disponible en español:

[![Creating and Distributing Python Packages ES](https://www.pydanny.com/static/packaging-course-es.jpg)](https://twoscoopspress.thinkific.com/courses/creating-and-distributing-python-packages-es)

---
## Built With

- [py.test](https://www.pytest.org)
- [Travis-CI](http://travis-ci.org/)
- [Tox](http://testrun.org/tox/)
- [Sphinx](http://sphinx-doc.org/)
- [ReadTheDocs](https://readthedocs.io/)
- [Bumpversion](https://github.com/peritus/bumpversion):
- [PyPI](https://pypi.python.org/pypi) 
- [Click](https://click.palletsprojects.com)

---

## Credits

This template is heavily based on [PyPackage](https://github.com/audreyr/cookiecutter-pypackage)
template from [@audreyr](https://github.com/audreyr).

It is also inspired by [Data Science](https://github.com/drivendata/cookiecutter-data-science) template from [Driven Data](http://drivendata.github.io/cookiecutter-data-science/).

---

## License

You can check out the full license [here](./LICENSE)

This project is licensed under the terms of the [MIT](https://choosealicense.com/licenses/mit/) license.

---