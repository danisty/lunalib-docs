Input
=====
An Input.

.. code-block:: html

    AddInput (<string> title, <string> text, <string> placeholder, <function> callback, <string> uniqueId, <boolean> inline)

.. important::
    For this control to be inline, the Size property must be specified.

Methods
-------
SetText ``nil``
***************

.. code-block:: html

    <void> SetText (<string> text)


Properties
----------
Title ``string``
****************
| Title of the Input.
| ``Input`` by default.

Text ``string``
***************
| Text of the Input. Changing it will also trigger the callback.
| Empty by default.

Placeholder ``string``
**********************
| Text that appears when nothing is written, a.k.a hint.
| Empty by default.

TextAlignment ``Enum.TextXAlignment``
*************************************
``Enum.TextXAlignment.Left`` by default.

ClearTextOnFocus ``boolean``
****************************
| Exactly what you read.
| ``false`` by default.

CallbackOnEnter ``boolean``
***************************
| Determines if you must press Enter for it to callback. If it's false it will callback once the focus is lost, no matter if you pressed Enter or not.
| ``false`` by default.

Callback ``function``
*********************
Called on focus lost.

Size ``int``
************
| Horizontal offset size of the control. If it's nil the scale will be 1, otherwise 0.
| ``nil`` by default.

Inline ``boolean``
******************
``false`` by default.