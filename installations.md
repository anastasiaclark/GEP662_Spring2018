## Install Anaconda's distribution of Python for **ALL USERS**
* Download Anaconda from https://www.anaconda.com/download
* Select the appropriate for your OS Python Graphical Installer. For this course, we will be using Python 3.
* Run the executable. For the location, install under C:\ drive. make a folder “Python3” if necessary.
  When asked, check **All Users** box and check **Add Anaconda to my PATH environment variable** box

## Packages to install
* geopandas
* rasterio
* statsmodels
* googlemaps
* mplleaflet
* bokeh
* folium
* osmnx
* networkx
* pandana 
* geoplot

To install the required packages, run anaconda prompt **as administrator**.
Make sure that conda-forge channel is your default channel, type following:  
`conda config --add channels conda-forge`

Install the packages:    
Type following one by one and when asked 'Proceed ([y]/n)?' type `y` and hit Enter. Most of the packages have a number of dependecnies that will be installed along the way. Just say `y` to them all.
* `conda install geopandas`
* `conda install rasterio`
* `conda install statsmodels`
* `conda install googlemaps`
* `conda install mplleaflet`
* `conda install bokeh`
* `conda install folium`
* `conda install networkx`
* `conda install pandana`
* `conda install geoplot`

