KeyBind
=======
A key binding is an association between a physical key on a keyboard and a parameter. A parameter can have any number of key bindings associated with it, and a particular key binding can control any number of parameters. Key bindings detects individual keys being pressed.

.. code-block:: html

    AddKeyBind (<string> title, <Enum.KeyCode> key, <function> callback, <string> uniqueId)


Methods
-------
SetKey ``nil``
**************
.. code-block:: html

    SetKey (<Enum.KeyCode> key)


Properties
----------
Title ``string``
****************
Title of the KeyBind.

Key ``Enum.KeyCode``
********************
Key for the KeyBind.

Callback ``function``
*********************
Called on Key pressed.