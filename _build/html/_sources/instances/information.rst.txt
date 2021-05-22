Information
===========
It displays information on screen.

.. code-block:: html

    AddInformation (<string> name, <boolean> bindToHeartbeat, <function> infoRetriever)

Methods
-------
Update ``nil``
**************
.. code-block:: html

    Update ()

Calls ``infoRetriever`` and updates the information on screen.

Properties
----------
Name ``string``
****************
| Name which will be displayed on Settings.
| ``Information`` by default.

InfoRetriever ``function``
**************************
This function will be called to know which information to display. You should return a table.

BindToHeartbeat ``boolean``
***************************
| This acts like a toggle. If ``true`` it will automatically update the information, else you'll have to manually do it will the ``Update`` method.
| ``false`` by default.

Visible ``boolean``
*******************
| Determines the visibility of the Information on screen.
| ``true`` by default.