############
Contributing
############

Contributions are always welcome and appreciated! Here are some ways you can contribute.

******
Issues
******

You can and should open an issue for any of the following reasons:

* you found a bug; steps for reproducing, or a pull request with a failing test case will be greatly appreciated
* you wanted to do something but did not find a way to do it after reading the documentation
* you believe the current way of doing something is more complicated or less elegant than it can be
* a related feature that you want is missing from the package

Please always check for existing issues before opening a new issue.

*************
Pull requests
*************

You want to contribute some code? Great! Here are a few steps to get you started:

#. **Fork the repository on GitHub**
#. **Clone your fork and create a branch for the code you want to add**
#. **Copy the folder django_admin_style at the root of your project**
#. **Add django_admin_style in INSTALLED_PACKAGE and run the command ``python manage.py migrate`` to have css files watched**


#. **Update documentation**

   If the change modifies behaviour or adds new features, you should update the documentation and ``README.rst``
   accordingly. Documentation is written in reStructuredText and built using Sphinx. You can find the sources in the
   ``docs`` directory.

   To build and check the docs, run

   .. code:: console

      (venv) $ tox -e docs

#. **Push your branch and submit a pull request to the master branch on GitHub**

   Incomplete/Work In Progress pull requests are encouraged, because they allow you to get feedback and help more
   easily.

#. **Your code must pass all the required GitHub Actions before it is merged**

   As of now, this consists of running on the supported Python, Django (see README),
   and building the docs succesfully.


.. _GitHub Actions: https://github.com/sabderemane/django-admin-style/actions
.. _PyPI: https://pypi.org/project/django-admin-style/
.. _on GitHub: https://github.com/sabderemane/django-admin-style/releases
.. _ReadTheDocs build: https://readthedocs.org/projects/django-admin-style/builds/