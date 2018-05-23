=====
Usage
=====

To use DjangoCMS Hero Slider in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'djangocms_hero_slider.apps.DjangocmsHeroSliderConfig',
        ...
    )

Add DjangoCMS Hero Slider's URL patterns:

.. code-block:: python

    from djangocms_hero_slider import urls as djangocms_hero_slider_urls


    urlpatterns = [
        ...
        url(r'^', include(djangocms_hero_slider_urls)),
        ...
    ]
