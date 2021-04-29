Container
=========
Slaves friendly

.. code-block:: html

    AddContainer (<string> title, <int> spacing)


Methods
-------
Toggle ``nil``
**************
.. code-block:: html

    <void> Toggle (<boolean> state)

Add<Control> ``Control``
************************
.. code-block:: html

    <Control> Add<Control> (...)

Example:

.. code-block:: lua

    local label = Container:AddLabel("Example")


Properties
----------
Title ``string``
****************
| Title of the Container.
| ``Container`` by default.

Spacing ``int``
***************
| Left margin of the Container content.
| ``2`` by default.