===================
djangocms-page-meta
===================

|Gitter| |PyPiVersion| |PyVersion| |Status| |TestCoverage| |CodeClimate| |License|

Meta tag information for django CMS 3 pages

Python: 2.7, 3.4, 3.5. 3.6

Django: 1.8 to 1.11

django CMS: 3.4 (and develop/3.5)

.. warning:: Since version 0.7, the support for Python 2.6, Python 3.3, Django<1.8 and django CMS<3.2
             has been dropped


**********
Quickstart
**********

#. A working django CMS environment is required for djangocms-page-meta to work. Refer to `django CMS documentation`_ for how to install and configure django CMS.

#. Install djangocms-page-meta::

        $ pip install djangocms-page-meta

   or from the repository::

        pip install -e git+https://github.com/nephila/djangocms-page-meta#egg=djangocms-page-meta

#. Then add it to INSTALLED_APPS along with its dependencies::

        'filer',
        'meta',
        'easy_thumbnails',
        'djangocms_page_meta',

#. Synchronize the database with syncdb::

        $ python manage.py syncdb

   or migrate::

        $ python manage.py migrate

#. Configuration:

   See `configuration`_ section in the documentation.

#. That's all!

Dependencies
============

* `django-filer`_ >= 1.2
* `django-meta`_  >= 1.3

*************
Documentation
*************

For package documentation see https://djangocms-page-meta.readthedocs.io/.


.. _django-filer: https://pypi.python.org/pypi/django-filer
.. _django-meta: https://pypi.python.org/pypi/django-meta
.. _configuration: https://djangocms-page-meta.readthedocs.io//en/latest/configuration.html
.. _django CMS documentation: https://django-cms.readthedocs.io/en/latest


.. |Gitter| image:: https://img.shields.io/badge/GITTER-join%20chat-brightgreen.svg?style=flat-square
    :target: https://gitter.im/nephila/applications
    :alt: Join the Gitter chat

.. |PyPiVersion| image:: https://img.shields.io/pypi/v/djangocms-page-meta.svg?style=flat-square
    :target: https://pypi.python.org/pypi/djangocms-page-meta
    :alt: Latest PyPI version

.. |PyVersion| image:: https://img.shields.io/pypi/pyversions/djangocms-page-meta.svg?style=flat-square
    :target: https://pypi.python.org/pypi/djangocms-page-meta
    :alt: Python versions

.. |Status| image:: https://img.shields.io/travis/nephila/djangocms-page-meta.svg?style=flat-square
    :target: https://travis-ci.org/nephila/djangocms-page-meta
    :alt: Latest Travis CI build status

.. |TestCoverage| image:: https://img.shields.io/coveralls/nephila/djangocms-page-meta/master.svg?style=flat-square
    :target: https://coveralls.io/r/nephila/djangocms-page-meta?branch=master
    :alt: Test coverage

.. |License| image:: https://img.shields.io/github/license/nephila/djangocms-page-meta.svg?style=flat-square
   :target: https://pypi.python.org/pypi/djangocms-page-meta/
    :alt: License

.. |CodeClimate| image:: https://codeclimate.com/github/nephila/djangocms-page-meta/badges/gpa.svg?style=flat-square
   :target: https://codeclimate.com/github/nephila/djangocms-page-meta
   :alt: Code Climate
