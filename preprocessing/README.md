In case you want to run these codes, you should run them on the following order:

- `surveys.ipynb` cleans, treats and postprocesses the survey data, adding salary data to each trip-taker
- `landuse&section_aggregation.ipynb` generates a building database, including land use and neighborhood-wealth characteristics
- `intermunicipal_travel_cost.ipynb` calculates travel fares between towns and regions for different public transport companies
- `create_road_network.ipynb` creates the pandana road network from OpenStreetMaps to calculate driving times from origin to destination
- `GTFS_transit_24.ipynb` creates the pandana transit networks (24, one for each hour) to calculate bus times from origin to destination
- `GTFS_train_24.ipynb` creates the pandana train networks (24, one for each hour) to calculate bus times from origin to destination


- `population_generation.ipynb` generates a placeholder of ~2500 workers commuting to a same place (industrial park) for users to create different scenarios with them.
