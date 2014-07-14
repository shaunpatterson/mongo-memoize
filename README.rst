mongo-memoize
=============

.. image:: https://badge.fury.io/py/mongo-memoize.png
    :target: http://badge.fury.io/py/mongo-memoize

.. image:: https://travis-ci.org/ikuyamada/mongo-memoize.png?branch=master
    :target: https://travis-ci.org/ikuyamada/mongo-memoize

A Python decorator library for instantly caching function results in MongoDB.

Basic Usage
-----------

.. code-block:: python

    from mongo_memoize import memoize

    @memoize()
    def some_function():
        pass
