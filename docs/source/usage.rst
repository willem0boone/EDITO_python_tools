Usage
==================

Search a dataset on title in a specific collection
--------------------------------------------------

.. code-block:: python

    from dtotools.search import search_on_title
    results = search_on_title(title="koster", collection="emodnet-biology")
    print(results)

This will return

.. code-block:: python

    [<Item id=bdbeb221-7656-52e5-9ade-4b3304db82cd>]

This Item is `a pystac item`_ which can be further explored using `PySTAC library`_ .

.. _a pystac item: https://pystac.readthedocs.io/en/stable/api/item.html
.. _PySTAC library: https://pystac.readthedocs.io/en/stable/index.html


Search a dataset on title in all collections
--------------------------------------------

.. code-block:: python

    from dtotools.search import search_on_title
    results = search_on_title(title="koster")