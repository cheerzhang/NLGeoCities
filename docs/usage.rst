Quick Start
==============================


Get city coordinates json file  from NLGeoCities
----------------------------------------------------

.. code-block:: python

    from nl_ego_cities import city_coords

    # Get json file
    cities = city_coords.city_json

    # Access city coordinates
    amsterdam_coords = cities["amsterdam"]
    print(f"Coordinates of Amsterdam: latitude: {amsterdam_coords['lat']}, longitude: amsterdam_coords['lon']}")


Processing dataframe with `get_lat_lon` function
----------------------------------------------------

.. code-block:: python

    from nl_ego_cities.load_city_data import get_lat_lon

    df['city_lat'], df['city_lon'] = get_lat_lon(df, 'city')

.. note::

