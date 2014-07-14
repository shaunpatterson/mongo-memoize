mongo-memoize
=============

A Python decorator library for memoizing functions instantly.

Basic Usage
-----------

.. code-block:: python
    from mongo_memoize import memoize

    @memoize()
    def some_function():
        pass
