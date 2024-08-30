## General info - OpenStreetMapRouteFinder
OpenStreetMap Route Finder is a Python-based project designed to find the shortest path between two points using OpenStreetMap (OSM) data. The project leverages the power of graph theory and geospatial analysis to calculate the shortest routes on undirected graphs, which are constructed from OSM road networks.

## Features

- **Shortest Path Calculation**: Computes the shortest path between two points using Dijkstra's algorithm.
- **Graph Construction**: Constructs undirected graphs from OpenStreetMap road networks.
- **Geospatial Analysis**: Utilizes geospatial libraries like `geopandas` and `shapely` for spatial data processing.
- **Visualization**: Provides visual representations of routes and graphs using `matplotlib` and `contextily`.


## Dependencies
The project relies on the following Python libraries:
- networkx
- geopandas
- shapely
- matplotlib
- contextily
- numpy
- osmnx

## Acknowledgments

This project uses data from [OpenStreetMap](https://www.openstreetmap.org). We would like to thank the OpenStreetMap community for their effort in collecting and maintaining the freely available geographic data.

OpenStreetMap data is made available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/), and any derived works are also subject to this license. If you use this data in your research or project, please provide proper attribution to OpenStreetMap and its contributors.
