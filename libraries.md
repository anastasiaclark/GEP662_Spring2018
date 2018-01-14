
| Package Name | Description/ Used For     
| :----------: |:-------------: 
|[Numpy](http://www.numpy.org/)|NumPy is the fundamental package for scientific computing with Python. Lots of other packages are built on Numpy. In GIS, we often use Numpy to work with raster data
|[Pandas](https://pandas.pydata.org/)|Pandas is powerful data analysis library. [Geopandas](http://geopandas.org/) as built on top of pandas. We will use Pandas extensively for data munging and preparation.
|[GeoPandas](http://geopandas.org/)|GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types. Geometric operations are performed by [shapely](http://toblerity.org/shapely/). Geopandas further depends on [fiona](http://toblerity.org/fiona/) for file access and descartes and [matplotlib](https://matplotlib.org/) for plotting. It's easy to integrate GeoPandas with other spatial tools and packages and it will be out go-to tool for all vector operations.
|[Bokeh](https://bokeh.pydata.org/en/latest/)|Bokeh is used to make interactive vizualizations. We will use Bokeh to bring data attributes in the map to life!
|[osmnx](https://osmnx.readthedocs.io/en/stable/)| With osmnx you can retrieve, construct, analyze, and visualize street networks from OpenStreetMap
|[Folium](https://folium.readthedocs.io/en/latest/)| Python library to make interactive web maps. You don't have to know javascript to make web maps; Folium is built on the Leaflet javascript library and provides a pythonic API to make web maps.
|[rasterstats](https://pypi.python.org/pypi/rasterstats)| Python module for summarizing geospatial raster datasets based on vector geometries. We will use this package to do zonal statistics.
|[rasterio](https://github.com/mapbox/rasterio)|Rasterio reads and writes geospatial raster data. Rasterio is built on top of GDAL, but it is a better alterntaive for working with rasters as it provides a more pythonic API.

