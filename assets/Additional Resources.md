---
layout: default
title: "Additional Resources"
permalink: /additional-resources
---

# Additional Resources
---

# Navigating the GEE documentation
The GEE documentation is comprehensive. Depending on what you are looking for, there are two main places in the official documentation to look: the **Guides** and the **Reference** (API documentation). 

> **Note:** Google Earth Engine (GEE) can be accessed through two programming languages: JavaScript, and Python. In this training we have used the Python interface, but be aware that some of the documentation will show examples in JavaScript instead of Python. However, the Earth Engine commands are similar in both languages. If needed, the `geemap` module that we use in this training has a function for converting JavaScript code to Python. A tutorial is available [here](https://geemap.org/notebooks/15_convert_js_to_py/), and the function documentation is [here](https://geemap.org/conversion/?h=js_snippet_to_py#geemap.conversion.jrc_hist_monthly_history).

## Guides
The [guides](https://developers.google.com/earth-engine/guides) are a good place to start for beginners, or when you aren't sure about the steps to carry out a certain task. 

### Quickstart guides
The quickstart guides are a great entry point for getting up and running with GEE. See the 
[Quickstart guide for GEE in Python](https://developers.google.com/earth-engine/guides/quickstart_python). 

> **Use this when:** you need a refresher on the basics of GEE with python, or help with setting up a Colab notebook to use with GEE. 
   
### Tutorials
The tutorials can help when you need extra guidance on how to carry out a specific task. In addition to the many tutorials available online, GEE has tutorials [here](https://developers.google.com/earth-engine/tutorials/videos) and a set of community tutorials [here](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api). *Note: See the left sidebar of each website for additional tutorials.*

> **Use this when:** you want guidance on how to carry out a specific task, such as [how to do time series analysis with GEE](https://developers.google.com/earth-engine/tutorials/videos#time-series-analysis)

## Reference (API documentation)
[The API documentation](https://developers.google.com/earth-engine/apidocs) provides information about specific functions in the `ee` interface to Python (and JavaScript). This can be helpful when you know which function you need to use, but need help with its exact usage, i.e., the inputs it accepts and the object it outputs.

> **Use this when:** you need more information about how to use a specific `ee` function.
> * Example: you want to use [ee.Geometry.BBox](https://developers.google.com/earth-engine/apidocs/ee-geometry-bbox) to define your region of interest, but you don't remember the order of bounding coordinates it accepts

# Python modules
There are many additional Python modules that you can use in your analysis besides `ee`. We've touched on a couple in this tutorial, but list here documentation for other Python modules commonly used for geospatial work in Python. 
- **[geemap](https://geemap.org/)**: use for mapping `ee` data
- **[numpy](https://numpy.org/doc/stable/)**: use for working with arrays and matrices
- **[scipy](https://docs.scipy.org/doc/scipy/)**: provides general algorithms common in math and science. In particular, see that [stats submodule](https://docs.scipy.org/doc/scipy/reference/stats.html) for using and defining statistical distributions. 
- **[matplotlib](https://matplotlib.org/stable/index.html)**: general Python plotting module
- **[pandas](https://pandas.pydata.org/docs/)**: Python module for handling tabular data (dataframes)
- **[geopandas](https://geopandas.org/en/stable/docs.html)**: extends `pandas` functionality to make it easier to perform geometric operations
- **[xarray](https://docs.xarray.dev/en/stable/)**: use for working with labelled multi-dimensional arrays (including data from netCDF and other raster files)
- **[cartopy](https://scitools.org.uk/cartopy/docs/latest/)**: use for mapping geospatial data in different projected coordinate systems

# Other resources

> **Note:** [Awesome Earth Engine](https://awesome.geemap.org/) is a great curated list of Google Earth Engine resources and much more comprehensive than what is included here.

- These [introductory slides](https://docs.google.com/presentation/d/1iZtkBNzl2HBWFT0wEhwCov89kyiBO7rSHcmMa6WNMa8/) from the GEE documentation give a nice overview of the different data types Earth Engine uses.
- The authors of the `geemap` package have several resources to help with learning GEE and geemap, including: 
	- a [series of GEE and geemap tutorials](https://www.youtube.com/playlist?list=PLAxJ4-o7ZoPccOFv1dCwvGI6TYnirRTg3) on the [Open Geospatial Solutions YouTube channel](https://www.youtube.com/@giswqs)
	- a [set of notebook-based tutorials](https://courses.geemap.org/)

## Free Courses
If you are interested in more training on Google Earth Engine and/or Python programming, there are many free courses available online. 

### GEE
- United Nations University Institute for Water, Environment, and Health (UNU-INWEH): [Spatial Data Management with Google Earth Engine](https://lc.unu.edu/courses/course-v1:UNU-INWEH+INWEH-19+2023-T2/about)
- Spatial Thoughts [End-to-End Google Earth Engine Course](https://courses.spatialthoughts.com/end-to-end-gee.html)

### Python
- University of Helsinki: [Python Programming MOOC 2025](https://programming-25.mooc.fi/)
- Coursera: [Python for Everybody](https://www.coursera.org/specializations/python#courses). See all course materials, including the book, [here](https://www.py4e.com)
- Codecademy: [Learn Python 3](https://www.codecademy.com/learn/learn-python-3). See additional Codecademy resources [here](https://www.codecademy.com/resources/docs/python)
