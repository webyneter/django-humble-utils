=====
Usage
=====

To use Django Humble Utils in a project, add it to your `INSTALLED_APPS`:

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
