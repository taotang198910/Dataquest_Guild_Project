# Visualizing Geographic Data

## Introduction:
In this project, I have explored the fundamentals of geographic coordinate systems and how to work with the basemap and folium library to plot geographic data points on maps. 

In most cases, we want to visualize latitude and longitude points on two-dimensional maps. Two-dimensional maps are faster to render, easier to view on a computer and distribute, and are more familiar to the experience of popular mapping software like Google Maps. Latitude and longitude values describe points on a sphere, which is three-dimensional. To plot the values on a two-dimensional plane, we need to convert the coordinates to the Cartesian coordinate system using a map projection.

A [map projection](https://en.wikipedia.org/wiki/Map_projection) transforms points on a sphere to a two-dimensional plane. When projecting down to the two-dimensional plane, some properties are distorted. Each map projection makes trade-offs in what properties to preserve and you can read about the different trade-offs [here](https://en.wikipedia.org/wiki/Map_projection#Metric_properties_of_maps). I used the [Mercator projection](https://en.wikipedia.org/wiki/Mercator_projection), because it is commonly used by popular mapping software.

The [matplotlib basemap toolkit](https://matplotlib.org/basemap/users/intro.html) is a library for plotting 2D data on maps in Python. Basemap does not do any plotting on it’s own, but provides the facilities to transform coordinates to one of 25 different map projections.

[Folium](https://folium.readthedocs.io/en/latest/) builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the Leaflet.js library. Manipulate your data in Python, then visualize it in on a Leaflet map via Folium.

## Installation:
- Install Basemap: `conda install basemap`
- Install Folium: `pip3 install folium`

You can view `Visualizing Geographic Data.ipynb` directly on github, or clone the repository and open on Jupyter Notebook.
