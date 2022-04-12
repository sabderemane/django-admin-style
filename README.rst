
django-admin-style
=====

.. image:: https://img.shields.io/github/v/release/sabderemane/django-admin-style   :alt: GitHub release (latest by date) 
.. image:: https://img.shields.io/pypi/v/django-admin-style   :alt: PyPI
.. image:: https://img.shields.io/readthedocs/django-admin-style   :alt: Read the Docs
.. image:: https://img.shields.io/github/last-commit/sabderemane/django-admin-style   :alt: GitHub last commit

Change the default admin to something more fresh

Installation
--------------
Python and Django are required.

You can install this package with pip::

    pip install django-admin-style


Quick start
-----------

1. Add "django_admin_style" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'django_admin_style',
    ]

2. Run ``python manage.py migrate`` to update style.

3. Start the development server and visit http://127.0.0.1:8000/admin/
   to view the administration.

Contributing
-------------

This is a an open-source project. We'll be delighted to receive your
feedback in the form of issues and pull requests. Before submitting your
pull request, please review our `contribution guidelines
<https://github.com/sabderemane/django-admin-style/CONTRIBUTING.md>`_.

We're grateful to all contributors who have helped create and maintain this package.
Contributors are listed at the `contributors <https://github.com/sabderemane/django-admin-style/graphs/contributors>`_
section.

