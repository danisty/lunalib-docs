Library
=======
I still remember the first line...

Instances
---------
.. toctree::
    :maxdepth: 1

    instances/tab
    instances/information

Methods
-------
Toggle ``nil``
**************
.. code-block:: html

    <void> Toggle ()

Toggle library UI visibility.

ShowNotification ``nil``
************************
.. code-block:: html

    <void> ShowNotification (<string> title, <string> message)

AddInformation |Information|_
******************************
.. code-block:: html

    <Information> AddInformation (<string> name, <boolean> bindToHeartbeat, <function> infoRetriever)

| If ``bindToHeartbeat`` is true it will automatically update the information, you won't need to call ``Update``.
| Example:

.. code-block:: lua

    Library:AddInformation("Random Number", true, function()
        return {
            tostring(math.random(100000, 999999))
        }
    end)

| When you add information you can hide it via Settings, a CheckBox will be added.
| If you want to add multiple lines of information, return a table with each line as a value. Example:

.. code-block:: lua

    Library:AddInformation("Multiple Random Numbers", true, function()
        return {
            tostring(math.random(100000, 999999)),
            tostring(math.random(100000, 999999)),
            tostring(math.random(100000, 999999)),
            tostring(math.random(100000, 999999))
        }
    end)

CreateTab |Tab|_
****************
.. code-block:: html

    <Tab> CreateTab (<string> name, <int> icon, <boolean> select)
    

GetTab |Tab|_
*************
.. code-block:: html

    <Tab> GetTab (<string> name)


Properties
----------
Title ``string``
****************
Library title.

Tabs ``table``
**************
Instanced Tabs.


.. |Tab| replace:: ``Tab``
.. _Tab: ./instances/tab.html

.. |Information| replace:: ``Information``
.. _Information: ./instances/information.html