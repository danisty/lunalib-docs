Tab
===
You put Categories here.

Instances
---------
.. toctree::
   :maxdepth: 1

   ../instances/category


Methods
-------
Select ``nil``
**************
.. code-block:: html

    <void> Select ()


CreateCategory |Category|_
**************************
.. code-block:: html

    <Category> CreateCategory (<string> title)


GetCategory |Category|_
***********************
.. code-block:: html

    <Category> GetCategory (<string> title)


Properties
----------
Name ``string``
***************
| Tab name.
| ``Tab`` by default.

Icon ``int``
************
| Tab icon.
| ``6728864703`` by default.

Selected ``boolean``
********************
| Whether the tab is selected or not.
| ``false`` by default.

Categories ``table``
********************
Categories of the Tab.

.. |Category| replace:: ``Category``
.. _Category: ./category.html