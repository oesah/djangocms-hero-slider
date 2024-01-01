=============================
DjangoCMS Hero Slider
=============================

.. image:: https://badge.fury.io/py/djangocms-hero-slider.svg
    :target: https://badge.fury.io/py/djangocms-hero-slider

.. image:: https://travis-ci.org/oesah/djangocms-hero-slider.svg?branch=master
    :target: https://travis-ci.org/oesah/djangocms-hero-slider

.. image:: https://codecov.io/gh/oesah/djangocms-hero-slider/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/oesah/djangocms-hero-slider

Hero Slider ffor Django CMS

Documentation
-------------

The full documentation is at https://djangocms-hero-slider.readthedocs.io.

Quickstart
----------

Install DjangoCMS Hero Slider::

    pip install djangocms-hero-slider

Add it to your `INSTALLED_APPS`:

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

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage

Sponsorship
-----------

This project is maintained by `Mathison AG | Mobile & Web Development <https://mathison.ch>`_.

Used by
-------

* `Stella Gastro | The best Restaurants, Bars and Cafés in Switzerland <https://stellagastro.ch>`_.
* `Lancer Express | The Swiss Army Knife for Freelancers <https://my.lancer.express>`_.
