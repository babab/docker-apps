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

Initial build and run::

   cd bitlbee
   wdocker init

   # or
   docker build -t bee .
   docker run -d -p 127.0.0.1:6667:6667 --name bee bee

Start, stop::

   wdocker start
   wdocker stop
