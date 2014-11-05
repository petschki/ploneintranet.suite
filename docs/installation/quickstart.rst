==========
Quickstart
==========

.. admonition:: Description

    This document gives you a quick overview on how to rapidly get a Plone Intranet installation up and running to test it out.


Testing
-------

After installation the dev environment, you can run the unit tests and the acceptance with::

    ./bin/test

There are a basic sets of tests for our javascript pattern modules in the ploneintranet.theme. These tests are controlled with a makefile
Go to the directory ``src/ploneintranet.theme``
and run::

    make check

.. todo::

    Here we want to include the Heroku Quickstart Button by Nejc
    Details can be found at https://github.com/niteoweb/heroku-buildpack-plone. An example for the deploy button can be found on that page at the very top.
