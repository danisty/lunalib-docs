Selector
========
:ref:`Selector`

.. code-block:: html

    AddSelector (<string> title, <table> items, <function> callback, <string> uniqueId)

Methods
-------
AddItem ``nil``
***************
.. code-block:: html

    <void> AddItem (<string> item)

RemoveItem ``nil``
******************
.. code-block:: html

    <void> RemoveItem (<string> item)

Toggle ``nil``
**************
.. code-block:: html

    <void> Toggle (<boolean> state)

Select ``nil``
**************
.. code-block:: html

    <void> Select (<string> item, <table> customError)

If the item doesn't exist, and ``customError`` is passed, it will show a notification instead of throwing an error. It follows the next structure

.. code-block:: lua

    {
        title="Error Title",
        message="Oh no, anyway"
    }


Properties
----------
Title ``string``
****************
| Title of the Selector.
| ``nil`` by default

.. note::
    If the title isn't defined, it won't be shown.

Item ``string``
***************
| Selected Item.
| ``nil`` by default.

Items ``table``
***************
| List of items.
| ``{}`` by default.

LastSelection ``string``
************************
| Last selected item.
| This property is Read-Only.
| ``nil`` by default.

Callback ``function``
*********************
Called on item selection