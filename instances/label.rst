Label
=====
A Label, it displays text.

.. code-block:: html

    AddLabel (<string> text, <Color3> color, <boolean> inline)


Properties
----------
Text ``string``
***************
| Text of the Label.
| ``Label`` by default.

Color ``Color3``
****************
| Color of the Text.
| ``nil`` by default.

.. note::
    If this property is defined it will ignore theme color changes. You can set it back to nil.

Inline ``boolean``
******************
``false`` by default.