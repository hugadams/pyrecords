Manager Classes
===============

Three core classes are provided by pyrecords.  The goal of these classes is to handle record data by enforcing type recasting and type checking automatically.  Most of this functionality is built into the abstract manager class, and then mutable and immutable behavior is imposed by the immutable and mutable manager classes respectively.  Although these classes are very different (immutable manager is a wrapper for NamedTuple objects; mutable manager inherits from Python's Object class), they have similar syntax and give the veil of similarity.

:mod:`abstractmanager` Module
-----------------------------

.. automodule:: pyrecords.Core.abstractmanager
    :members:
    :undoc-members:
    :show-inheritance:

:mod:`immutablemanager` Module
------------------------------

.. automodule:: pyrecords.Core.immutablemanager
    :members:
    :undoc-members:
    :show-inheritance:

:mod:`mutablemanager` Module
----------------------------

.. automodule:: pyrecords.Core.mutablemanager
    :members:
    :undoc-members:
    :show-inheritance:

