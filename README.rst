=============================
Django Humble Utils
=============================

.. image:: https://badge.fury.io/py/django-humble-utils.svg
    :target: https://badge.fury.io/py/django-humble-utils

.. image:: https://travis-ci.org/webyneter/django-humble-utils.svg?branch=master
    :target: https://travis-ci.org/webyneter/django-humble-utils

.. image:: https://codecov.io/gh/webyneter/django-humble-utils/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/webyneter/django-humble-utils

Your project description goes here

Documentation
-------------

The full documentation is at https://django-humble-utils.readthedocs.io.

Quickstart
----------

Install Django Humble Utils::

    pip install django-humble-utils

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_humble_utils.apps.DjangoHumbleUtilsConfig',
        ...
    )

Add Django Humble Utils's URL patterns:

.. code-block:: python

    from django_humble_utils import urls as django_humble_utils_urls


    urlpatterns = [
        ...
        url(r'^', include(django_humble_utils_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
