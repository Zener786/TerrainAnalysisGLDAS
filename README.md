# TerrainAnalysisGLDAS
Terrain analysis by extracting GLDAS data
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Zener786/TerrainAnalysisGLDAS/master)
.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/Zener786/TerrainAnalysisGLDAS/master
 
 Pre-requisite libraries are mentioned in environment.yml.
 
 Through the program we have extracted the GLDAS of a particular time period of a particular location.
 
 We have here extracted the GLDAS runoff data of July month 2013 and then we filtered the 6-9am image id's so that we get the approximate correct value.
 
 Data was in kg/m2/3hr.
 We applied unit converstion and converted the data into volumetric flow ie.m3/sec
 
We have done this for a particular point.

Further we have extracted a .geotiff file of the catchment area you've provided us...
We will extract the pixels and will compute their values and will provide you with the final calculated values of that catchment.

