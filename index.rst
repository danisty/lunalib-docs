Welcome Sowd
============
I was bored and decided to, since I had to document the library, learn about readthedocs. Hope everything is clear enough, you can always ask any doubts.

Contents
--------
.. toctree::
    :maxdepth: 1

    library

.. toctree::
    :maxdepth: 2

    controls

General Information
-------------------
All instances inherit the next properties

- ``__Instance``: RBX Instance of the control.
- ``__Attributes``: Attributes of the control.
- ``__Methods``: Methods of the control.

All properties/attributes can be modified unless they are read-only, for example, you could change the Color of a ColorPicker by calling the ``SetColor`` method or by changing the ``Color`` property, whichever option you like the most.