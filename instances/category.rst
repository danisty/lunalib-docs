Category
========
You put Controls here.

.. code-block:: html

    CreateCategory (<string> title)

Controls
--------
- :ref:`Label`
- :ref:`Button`
- :ref:`CheckBox`
- :ref:`ColorPicker`
- :ref:`Slider`
- :ref:`Input`
- :ref:`DropDown`
- :ref:`Container`
- :ref:`Selector`


Methods
-------
GetControl ``Control``
**********************
.. code-block:: html

    <Control> GetControl (<string> attribute, <Object> value)

Get Control by attribute.

Add<Control> ``Control``
************************
.. code-block:: html

    <Control> Add<Control> (...)

Example:

.. code-block:: lua

    local label = Category:AddLabel("Example")


Properties
----------
Title ``string``
****************
| Title of the Category.
| ``Category Title`` by default.

Controls ``table``
******************
Controls of the Category.