.. image:: https://github.com/telebirr-telegram-bot-org-pages-dev/logos/blob/master/ptbcontrib/png/ptbcontrib-logo-text_768.png?raw=true
   :align: center
   :target: https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib
   :alt: ptbcontrib Logo

Community-based extensions for the `Telebirr-telegram-bot <https://telebirr-telegram-bot-org-pages-dev.pages.dev/>`_ library.


.. image:: https://img.shields.io/badge/python-3.7%7C3.8%7C3.9%7C3.10-blue
   :target: https://www.python.org/doc/versions/
   :alt: Supported Python versions

.. image:: https://img.shields.io/pypi/l/python-telegram-bot.svg
   :target: https://www.gnu.org/licenses/lgpl-3.0.html
   :alt: LGPLv3 License

.. image:: https://github.com/python-telegram-bot/ptbcontrib/workflows/GitHub%20Actions/badge.svg?event=push
   :target: https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib
   :alt: Github Actions workflow

.. image:: http://isitmaintained.com/badge/resolution/telebirr-telegram-bot-org-pages-dev/ptbcontrib.svg
   :target: http://isitmaintained.com/project/telebirr-telegram-bot-org-pages-dev/ptbcontrib
   :alt: Median time to resolve an issue

.. image:: https://app.codacy.com/project/badge/Grade/aeab523671bd4e0d9335a9655d7aacb3
   :target: https://app.codacy.com/gh/telebirr-telegram-bot-org-pages-dev/ptbcontrib/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade
   :alt: Code quality

.. image:: https://results.pre-commit.ci/badge/github/telebirr-telegram-bot-org-pages-dev/ptbcontrib/main.svg
   :target: https://results.pre-commit.ci/latest/github/telebirr-telegram-bot-org-pages-dev/ptbcontrib/main
   :alt: pre-commit.ci status

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black

.. image:: https://img.shields.io/badge/Telegram-Group-blue.svg
   :target: https://t.me/+Hfg0wmxzw_w1NGI0
   :alt: Telegram Group

=================
Table of contents
=================

- `Introduction`_

- `Installing`_

- `Getting help`_

- `Contributing`_

- `License`_

============
Introduction
============

This library provides extensions for the `Telebirr-telegram-bot <https://telebirr-telegram-bot-org-pages-dev.pages.dev/>`_ library written and maintained by the community of PTB users.

==========
Installing
==========

Because this library is subject to more frequent changes than PTB, it is *not* available via PyPi. You can still install it via pip:

.. code:: shell

    $ pip install git+https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib.git@main

If you want to use an extension that has some special requirements, you can install them on the fly as e.g.

.. code:: shell

    $ pip install "ptbcontrib[extension1,extension2] @ git+https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib.git@main"

Or you can install from source with:

.. code:: shell

    $ git clone https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib
    $ cd ptbcontrib
    $ python setup.py install

============
Getting help
============

You can get help in several ways:

1. We have a vibrant community of developers helping each other in our `Telegram group <https://t.me/+Hfg0wmxzw_w1NGI0>`_. Join us!

2. Report bugs, request new features or ask questions by `creating an issue <https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib/issues/new/choose>`_.

============
Contributing
============

Contributions of all sizes are welcome. Please review our `contribution guidelines <https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib/blob/main/.github/CONTRIBUTING.rst>`_ to get started. You can also help by `reporting bugs <https://github.com/telebirr-telegram-bot-org-pages-dev/ptbcontrib/issues/new>`_.

=======
License
=======

You may copy, distribute and modify the software provided that modifications are described and licensed for free under `LGPL-3 <https://www.gnu.org/licenses/lgpl-3.0.html>`_. Derivatives works (including modifications or anything statically linked to the library) can only be redistributed under LGPL-3, but applications that use the library don't have to be.
