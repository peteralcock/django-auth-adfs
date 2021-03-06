ADFS Authentication for Django
==============================

.. image:: https://readthedocs.org/projects/django-auth-adfs/badge/?version=latest
    :target: http://django-auth-adfs.readthedocs.org/en/latest/?badge=latest
    :alt: Documentation Status
.. image:: https://img.shields.io/pypi/v/django-auth-adfs.svg
    :target: https://pypi.python.org/pypi/django-auth-adfs
.. image:: https://travis-ci.org/jobec/django-auth-adfs.svg?branch=master
    :target: https://travis-ci.org/jobec/django-auth-adfs
.. image:: https://codecov.io/github/jobec/django-auth-adfs/coverage.svg?branch=master
    :target: https://codecov.io/github/jobec/django-auth-adfs?branch=master

A Django authentication backend for Microsoft ADFS 3.0

* Free software: BSD License
* Homepage: https://github.com/jobec/django-auth-adfs
* Documentation: http://django-auth-adfs.readthedocs.org/

Features
--------

* Integrates Django with Active Directory through Microsoft ADFS 3.0 by using OAuth2.
* Provides seamless single sign on (SSO) for your Django project on intranet environments.
* Auto creates users and adds them to Django groups based on info in JWT claims received from ADFS.

Contents
--------

.. toctree::
   :maxdepth: 3

   install
   configuration
   adfs_config_guide
   extras
   troubleshooting
   adfs_oauth
   contributing
   changelog
