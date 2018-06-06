docker-apps
==============================================================================

A collection of various apps in Docker containers, meant to be run locally.

Each Dockerfile is configured with #wd# comments for managing images and
containers with wdocker_.

You can install wdocker with pip::

   sudo pip install wdocker

.. _wdocker: https://github.com/babab/wdocker

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
