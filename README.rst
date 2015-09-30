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

   # or
   docker build -t bee .
   docker run -d -p 127.0.0.1:6667:6667 --name bee bee

php7
----

::

   cd php7
   wdocker init

   # or
   docker build -t php7 .
   docker run -d -p 127.0.0.1:80:80 --name php7 php7

mysql
-----

::

   cd mysql
   wdocker init

   # or
   docker build -t mysql .
   docker run -d --name mysql mysql

memcached
---------

::

   cd memcached
   wdocker init

   # or
   docker build -t memcached .
   docker run -d --name memcached memcached
