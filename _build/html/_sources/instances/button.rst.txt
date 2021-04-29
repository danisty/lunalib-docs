Button
======
You click it, and calls back a function, that easy.

.. code-block:: html

    AddButton (<string> title, <function> callback, <boolean> inline)

Methods
-------
Click ``nil``
*************
.. code-block:: html

    <void> Click ()


Properties
----------
Text ``string``
***************
| Text of the Button.
| ``Button`` by default.

Callback ``function``
*********************
Callback on click.

Color ``Color3``
****************
| Color of the Button.
| ``nil`` by default.

.. note::
    If this property is defined it will ignore theme color changes. You can set it back to nil.

ResizeToBounds ``boolean``
**************************
| Determines if the Button should be resized to the Text bounds.
| ``true`` by default.

Disabled ``boolean``
********************
``false`` by default.

InverseHovering ``boolean``
***************************
| Determines if the Button hovering should be brighter ``false`` or darker ``true``.
| ``false`` by default.

TextAlignment ``Enum.TextXAlignment``
*************************************
``Enum.TextXAlignment.Left`` by default.

Inline ``boolean``
******************
``false`` by default.