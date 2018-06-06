docker-apps
==============================================================================

A small collection of various Dockerfiles, meant to build containers
that run locally in a development environment. Each Dockerfile is
configured with ``#wd#`` comments for managing images and containers
with wdocker_.

The Dockerfiles are small examples of using wdocker in different
contexts and this repository focuses more on the Dockerfiles than the
actual applications that are built. They can of course be used as a
starting point for creating production ready containers of mentioned
applications or similar setups. The examples are explicitly released
into the public domain using the Unlicense_.

You can install wdocker with pip::

   sudo pip install wdocker

.. _wdocker: https://github.com/babab/wdocker
.. _Unlicense: https://unlicense.org/

bitlbee
-------

::

   cd bitlbee
   wdocker init

php7
----

::

   cd php7
   wdocker init

mysql
-----

::

   cd mysql
   wdocker init

memcached
---------

::

   cd memcached
   wdocker init
