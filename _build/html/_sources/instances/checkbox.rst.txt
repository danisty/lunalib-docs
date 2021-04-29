CheckBox
========
Also known as a toggle, it's like using a lever.

.. code-block:: html

    AddCheckBox (<string> title, <boolean> checked, <function> callback, <string> uniqueId, <boolean> inline)

Methods
-------
Toggle
******
.. code-block:: html

    <nil> Toggle (<boolean> state)

Toggle the CheckBox. If ``state`` is passed, it will toggle to that state.


Properties
----------
Title ``string``
****************
| Title of the CheckBox.
| ``CheckBox`` by default.

Checked ``boolean``
*******************
| Whether the CheckBox is checked or not.
| ``false`` by default.

Callback ``function``
*********************
Called back once toggled.

Inline ``boolean``
******************
``false`` by default.