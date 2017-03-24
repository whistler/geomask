# Geomask

Python library to convert polygons in GeoJSON, Shapefile and WKT format to
raster masks and vice versa. It can be used for data visualizations and machine
learning on images.

## Installation

    pip install geomask

## Usage

    import geomask

### Rasterize GeoJSON to create a image mask

    image = geomask.rasterize(geojson)

### Create a GeoJSON from a image mask

    geojson = geomask.geojson(image, epsilon, min_area)
