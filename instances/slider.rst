Slider
======
It's where you slide, I think.

.. code-block:: html

    AddSlider (<string> title, <int> min, <int> max, <int> value, <int> decimals, <function> callback, <string> uniqueId, <boolean> inline)

.. important::
    For this control to be inline, the Size property must be specified.

Methods
-------
Change
******

.. code-block:: html

    <void> Change (<int> value)


Properties
----------
Title ``string``
****************
| Title of the Slider.
| ``Slider`` by default.

Min ``int``
***********
| Minimun value.
| ``0`` by default.

Max ``int``
***********
| Maximun value.
| ``10`` by default.

Value ``int``
*************
| These descriptions are being quite useless.
| ``0`` by default.

Decimals ``int``
****************
| Value decimals. If set to 2, you will get values with 2 decimals ``1.23``, if set to 9 ``1.234567890``, and so on.
| ``0`` by default.

Size ``int``
************
| Horizontal offset size of the control. If it's nil the scale will be 1, otherwise 0.
| ``nil`` by default.

Callback ``function``
*********************
Called on value changed.

Inline ``boolean``
******************
``false`` by default. 