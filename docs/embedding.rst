Embedding
========

MyRoute-app allows developers to embed the following objects:

- :ref:`Map <map-label>`
- :ref:`Route summary <route-label>`
- :ref:`Tracklog summary <tracklog-label>`

This page will show how this is achieved and specifies all available customization options.

.. _map-label:

Map
--------

Maps can be embedded by using an iframe with `https://www.myrouteapp.com/embed/map` as source.

A plain example of the html iframe:

.. code-block:: html

    <iframe src="https://www.myrouteapp.com/embed/map?lang=nl&amp;lat=52.370216&amp;lon=4.895168&amp;zoom=10" width="100%" height="500"></iframe>


The map can be customized by altering the url parameters as shown below:

+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| Parameter       | Datatype   | Default    | Options          | Description                                                                |
+=================+============+============+==================+============================================================================+
| partner         | Integer    | None       | Your partner ID  | Show discount and receive commission                                       |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| user            | Integer    | None       | Your user ID     | Only show content of this user                                             |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| folder          | Integer    | None       | User's folder ID | Show user's content in this folder                                         |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| type            | String     | all        | - all            | Filter content based on type                                               |
|                 |            |            | - route          |                                                                            |
|                 |            |            | - track          |                                                                            |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| mode            | String     | all        | - all            | Filter content based on travel mode                                        |
|                 |            |            | - drive          |                                                                            |
|                 |            |            | - bike           |                                                                            |
|                 |            |            | - walk           |                                                                            |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| fitmarkers      | Boolean    | false      |                  | Fits all markers inside map view. lat, lng and zoom will be ignored.       |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| lat             | Float      | None       |                  | Sets initial position                                                      |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| lon             | Float      | None       |                  | Sets initial position                                                      |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+
| zoom            | Integer    | 8          | 1 - 15           | Sets initial zoom level                                                    |
+-----------------+------------+------------+------------------+----------------------------------------------------------------------------+

.. _route-label:

Route summary
------------

1. View a route on www.myrouteapp.com
2. Press "Share" -> "Embed"
3. Copy the generated code and use it wherever you like.

.. _tracklog-label:

Tracklog summary
----------

1. View a tracklog on www.myrouteapp.com
2. Press "Share" -> "Embed"
3. Copy the generated code and use it wherever you like.
