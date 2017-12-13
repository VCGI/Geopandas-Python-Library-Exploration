# Python/Geopandas Data Cleaning, Transformation and Exploration

### Summary
In these notebooks there is an exploration of the Python Geopandas package and its implementation to load, transform and explore dataset. Since Geopandas can take both zipped and unzipped files, each method will be explored. Please feel free to fork and repurpose this information. For any questions please contact http://vcgi.vermont.gov.

### Tools
This is a Python 3.6 Jupyter notebook, to install I recommend https://www.anaconda.com/download/.

[GeoPandas](http://geopandas.org) extends the datatypes used by pandas to allow spatial operations on geometric type. Geometric operations are performed by shapely. Geopandas further depends on fiona for file access and descartes and matplotlib for plotting.

The goal of GeoPandas is to make working with geospatial data in python easier. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. GeoPandas enables you to easily do operations in python that would otherwise require a spatial database such as PostGIS.

How to install geopandas: http://geopandas.org/install.html#installing-geopandas

### Dependencies
Installation via conda should also install all dependencies, but a complete list is as follows:

* numpy - Fundamental package for scientific computing with Python http://www.numpy.org/
* pandas (version 0.15.2 or later) - High-performance, easy-to-use data structures and data analysis tools http://pandas.pydata.org/
* shapely - Python package for manipulation and analysis of planar geometric objects (based on widely deployed GEOS) https://pypi.python.org/pypi/Shapely
* fiona - Reading and writing spatial data (alternative for geopandas) https://pypi.python.org/pypi/Fiona/1.7.9.post1
* six - provides utility functions for compatiblity on both Python versions https://pypi.python.org/pypi/six
* pyproj - Performs cartographic transformations and geodetic computations https://pypi.python.org/pypi/pyproj

### Optional dependencies:

* geopy 0.99 (optional; for geocoding) - Geocoding library: coordinates to address <-> address to coordinates. https://pypi.python.org/pypi/geopy/0.99
* psycopg2 (optional; for PostGIS connection) https://pypi.python.org/pypi/psycopg2
* rtree (optional; spatial index to improve performance) https://pypi.python.org/pypi/Rtree/

### Plotting Packages
* matplotlib - 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments https://matplotlib.org/
* descartes - Use geometric objects as matplotlib paths and patches https://pypi.python.org/pypi/descartes
* pysal - library of spatial analysis functions to support the development of high level applications http://pysal.readthedocs.io/en/latest/
* shapely - manipulation of geometrict shapes https://pypi.python.org/pypi/Shapely
* bokeh - interactive mapping https://bokeh.pydata.org/en/latest/

There was one absolutely amazing site with lessons from the University of Helsinki on GeoPandas, much of which was adopted and modified for this notebook. Take a look at https://automating-gis-processes.github.io/2016/index.html for a more detailed walk through.
