DropDown
========
| Ain't nobody bringing us **down** **down** **down** **down** **down** **down**
| they can try but we're gonna wear the crown [...]

.. code-block:: html

    AddDropDown (<string> title, <table> items, <string> default, <function> callback, <string> uniqueId)

.. important::
    For this control to be inline, the Size property must be specified.


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


SetItems ``nil``
****************
.. code-block:: html

    <void> SetItems (<table> items, <string> default)

Calling the function instad of changing ``Items`` has the advantage of directly setting the item to select, ``default``.

Clear ``nil``
*************
.. code-block:: html

    <void> Clear ()

Clear all items.


Properties
----------
Title ``string``
****************
| Title of the DropDown.
| ``DropDown`` by default.

Item ``string``
***************
| Selected Item.
| ``nil`` by default.

Items ``table``
***************
| List of items.
| ``{}`` by default.

Size ``int``
************
| Horizontal offset size of the control. If it's nil the scale will be 1, otherwise 0.
| ``nil`` by default.

Callback ``function``
*********************
Called on item selection

Inline ``boolean``
******************
``false`` by default.