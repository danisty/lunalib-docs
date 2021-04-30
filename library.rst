Library
=======
I still remember the first line...

Instances
---------
.. toctree::
   :maxdepth: 1

   instances/tab


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