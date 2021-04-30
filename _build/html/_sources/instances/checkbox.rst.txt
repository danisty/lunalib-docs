CheckBox
========
Also known as a toggle, it's like using a lever.

.. code-block:: html

    AddCheckBox (<string> title, <boolean> checked, <Enum.KeyCode> keybind, <function> callback, <string> uniqueId, <boolean> inline)

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

KeyBind ``Enum.KeyCode``
************************
| Call back on binded key press.
| ``nil`` by default.

KeyBindEnabled ``boolean``
**************************
| It'll be ``true`` if you pass a ``Enum.KeyCode`` or ``true`` to ``KeyBind`` on the constructor.
| It'll be ``false`` if nothing is passed, ``nil``, or ``false``.

Callback ``function``
*********************
Called back once toggled.

Inline ``boolean``
******************
``false`` by default.