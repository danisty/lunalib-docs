ColorPicker
===========
色を選ぶ

.. code-block:: html

    AddColorPicker (<string> title, <Color3> color, <function> callback, <string> uniqueId)

Methods
-------
SetColor
********

.. code-block:: html

    <void> SetColor (<Color3> color)


Toggle
******

.. code-block:: html

    <void> Toggle (<boolean> state)

Show/Hide picker.

Properties
----------
Title ``string``
****************
Title of the ColorPicker.

Color ``Color3``
****************
Color picked.

Callback ``function``
*********************
Called on color changed.