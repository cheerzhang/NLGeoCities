NLGeoCities Quick Start
==============================


.. code-block:: python

    from nl_ego_cities import city_coords

    # Get json file
    cities = city_coords.city_json

    # Access city coordinates
    amsterdam_coords = cities["amsterdam"]
    print(f"Coordinates of Amsterdam: latitude: {amsterdam_coords['lat']}, longitude: amsterdam_coords['lon']}")

