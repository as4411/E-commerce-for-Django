.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/logos/oscar.png
    :target: http://oscarcommerce.com

===================================
Domain-driven e-commerce for Django
===================================


Oscar is an e-commerce framework for Django designed for building domain-driven
sites.  It is structured such that any part of the core functionality can be
customised to suit the needs of your project.  This allows a wide range of
e-commerce requirements to be handled, from large-scale B2C sites to complex B2B
sites rich in domain-specific business logic.

Contents:

.. contents:: :local:

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/oscarcommerce.thumb.png
    :target: http://oscarcommerce.com

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/readthedocs.thumb.png
    :target: https://django-oscar.readthedocs.io/en/latest/

Further reading:

* `Official homepage`_
* `Sandbox site`_ (automatically deployed via the official docker sandbox image)
* `Documentation`_ on the excellent `readthedocs.org`_
* `Docker image`_ on http://hub.docker.com/
* `django-oscar group`_ - mailing list for questions and announcements
* `Twitter account for news and updates`_
* `Discord`_
* `PyPI page`_
* `Transifex project`_ - translating Oscar made easy

.. start-no-pypi

Continuous integration status:

.. image:: https://github.com/django-oscar/django-oscar/workflows/Tests/badge.svg

.. image:: http://codecov.io/github/django-oscar/django-oscar/coverage.svg?branch=master
    :alt: Coverage
    :target: http://codecov.io/github/django-oscar/django-oscar?branch=master

.. image:: https://requires.io/github/django-oscar/django-oscar/requirements.svg?branch=master
     :target: https://requires.io/github/django-oscar/django-oscar/requirements/?branch=master
     :alt: Requirements Status

PyPI status:

.. image:: https://img.shields.io/pypi/v/django-oscar.svg
    :target: https://pypi.python.org/pypi/django-oscar/

Docs status:

.. image:: https://readthedocs.org/projects/django-oscar/badge/
   :target: https://readthedocs.org/projects/django-oscar/
   :alt: Documentation Status

.. end-no-pypi

.. _`Official homepage`: http://oscarcommerce.com
.. _`Sandbox site`: https://latest.oscarcommerce.com
.. _`Docker image`: https://hub.docker.com/r/oscarcommerce/django-oscar-sandbox/
.. _`Documentation`: https://docs.oscarcommerce.com/en/latest/
.. _`readthedocs.org`: http://readthedocs.org
.. _`Twitter account for news and updates`: https://twitter.com/#!/django_oscar
.. _`django-oscar group`: https://groups.google.com/forum/?fromgroups#!forum/django-oscar
.. _`PyPI page`: https://pypi.python.org/pypi/django-oscar/
.. _`Transifex project`: https://www.transifex.com/projects/p/django-oscar/
.. _`Discord`: https://discord.gg/NMwfZuJnJZ

Core team:

- `David Winterbottom`_ (Twitter `@codeinthehole`_)
- `Maik Hoepfel`_ (Twitter `@maikhoepfel`_)
- `Markus Bertheau`_
- `Michael van Tellingen`_
- `Alexander Gaevsky`_
- `Samir Shah`_

.. _`David Winterbottom`: https://github.com/codeinthehole
.. _`@codeinthehole`: https://twitter.com/codeinthehole
.. _`Maik Hoepfel`: https://github.com/maikhoepfel
.. _`@maikhoepfel`: https://twitter.com/maikhoepfel
.. _`Markus Bertheau`: https://github.com/mbertheau
.. _`Michael van Tellingen`: https://github.com/mvantellingen
.. _`Alexander Gaevsky`: https://github.com/sasha0
.. _`Samir Shah`: https://github.com/solarissmoke


Supported versions
------------------

The currently supported versions of Oscar are:

+---------+----------------+
| Version | End of support |
+=========+================+
| 3.2 LTS | January 2026   |
+---------+----------------+
| 3.1     | April 2022     |
+---------+----------------+
| 3.0     | May 2021       |
+---------+----------------+
| 2.2 LTS | August 2023    |
+---------+----------------+

Supported versions are eligible for fixes for data loss bugs and security issues. Releases designated as
Long-term support (LTS) releases will receive support for an extended period of 3 years from their release date.


Screenshots
-----------

Sandbox
~~~~~~~

These are screenshots from the 'sandbox' example site that ships with
Oscar.  It sports a simple design built with Twitter's Bootstrap_ and provides a
good starting point for rapidly building elegant e-commerce sites.

.. _Bootstrap: https://getbootstrap.com/

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/browse.thumb.png
    :target: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/browse.png

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/detail.thumb.png
    :target: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/detail.png

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/basket.thumb.png
    :target: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/basket.png

.. image:: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/dashboard.thumb.png
    :target: https://github.com/django-oscar/django-oscar/raw/master/docs/images/screenshots/dashboard.png

The sandbox site is also available to browse at https://latest.oscarcommerce.com.

The sandbox site can be set-up locally `in 5 commands`_.  Want to
make changes?  Check out the `contributing guidelines`_.

.. _`in 5 commands`: https://django-oscar.readthedocs.io/en/latest/internals/sandbox.html#run-the-sandbox-locally
.. _`contributing guidelines`: https://django-oscar.readthedocs.io/en/latest/internals/contributing/index.html


Extensions
----------

The following extensions are stable and ready for use:

* django-oscar-api_ - RESTful JSON API for django-oscar

* django-oscar-odin_ - Odin Resources and mappings to Oscar models

* django-oscar-adyen_ - Integration with the Adyen payment gateway

* django-oscar-datacash_ - Integration with the DataCash_ payment gateway

* django-oscar-paypal_ - Integration with PayPal.  This currently supports both
  `Express Checkout`_ and `PayFlow Pro`_.

* django-oscar-paymentexpress_ - Integration with the `Payment Express`_ payment
  gateway

* django-oscar-accounts_ - Managed accounts (can be used for giftcard
  functionality and loyalty schemes)

* django-oscar-stores_ - Physical stores integration (opening hours, store
  locator etc)

* django-oscar-sagepay-direct_ - Integration with "DIRECT" part of Sagepay's API

* django_oscar_docdata_ - Integration with Docdata_ payment gateway.

* django_oscar_invoices_ - Invoices or receipts generation for the
  Oscar






Contributing to the Project
---------------------------

We welcome contributions to the project! Whether it's a bug fix, a new feature, or just some documentation improvements, your contributions are greatly appreciated.

To contribute, please follow these steps:

Fork the project repository on GitHub.
Clone your forked repository to your local machine.
Create a new branch for your changes.
Make your changes, and commit them with clear commit messages.
Push your changes to your forked repository.
Open a pull request on the original project repository, explaining your changes.
Please note that all contributions are subject to review, and may be modified or rejected if they do not meet the project's standards.

Code of Conduct
---------------

We want everyone involved in the project to feel safe and respected, regardless of their background or identity. As such, we have adopted the following Code of Conduct:

Our Pledge 
----------

In the interest of fostering an open and welcoming environment, we pledge to:

Be friendly and welcoming to all contributors.
Respect differing viewpoints and experiences.
Accept constructive criticism and feedback graciously.
Focus on what is best for the community and the project.

Our Standards
-------------

We expect all contributors to:

Use welcoming and inclusive language.
Be respectful of differing viewpoints and experiences.
Gracefully accept constructive criticism.
Focus on what is best for the community and the project.

Our Responsibilities
--------------------

Project maintainers are responsible for:

Enforcing the Code of Conduct.
Investigating and addressing reported violations of the Code of Conduct.
Making clear and fair decisions about disciplinary actions for violations of the Code of Conduct.
Scope
This Code of Conduct applies to all contributors, both online and offline, in all project spaces, including but not limited to project forums, mailing lists, GitHub repositories, and in-person events.

