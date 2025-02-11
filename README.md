# Historical_Earthquake_Dataset
<p align="justify">
This dataset contains epicenters and event information for more than 70000 earthquakes occurring between the years 0 and 2024 AD. The dataset combines 3 different sources featuring earthquakes with magnitudes of 5.5 and above and is updated on a yearly basis. It provides the user with a comprehensive view of past seismicity for an area of interest.
</p>

# Dataset Description
<p align="justify">
The earthquake data includes more than 70.000 epicenters from three distinct data sources as described below. The dataset incorporates historical earthquakes as small as magnitude 5.5 and as deep as 70 km from the years 0 to 2024.
Seismicity data from 3 different sources is combined in this dataset:
  
•	For the period 0 to 1899, earthquake data are from the National Geophysical Data Center / World Data Service (NGDC/WDS) Significant Earthquake Database, (http://www.ngdc.noaa.gov/). This database contains information on destructive earthquakes that meet at least one of the following criteria: moderate damage (approximately $1 million or more), 10 or more deaths, magnitude 7.5 or greater, Modified Mercalli Intensity X or greater, or the earthquake generated a tsunami. The reliability of parameters for individual earthquakes can vary from case to case, and some minor modifications have been made by Swiss Re. Many earthquakes in this catalog are included despite an unknown depth or magnitude. 

•	For the period 1900 to 2020, earthquake data are from the ISCGEM Global Instrumental Earthquake Catalogue, Version1.03 (http://www.isc.ac.uk/iscgem/). This catalogue was generated using uniform techniques to obtain the magnitude and location of historic earthquakes. As such, the earthquake information from this catalog can be considered reliable. The catalog includes nearly all earthquakes greater than magnitude 7.5 that have occurred since 1900, greater than 6.25 since 1918 and greater than 5.5 since 1960. 

•	For the period 2019 to 2024, earthquake data are taken from the United States Geological Survey (USGS) Advanced National Seismic System (ANSS) comprehensive catalog (ComCat) based on a search for global earthquakes with magnitude 5.5 or greater and depth of 70 km or less (http://earthquake.usgs.gov/earthquakes/search/). The catalog is a compilation of earthquake parameters produced by contributing seismic networks.
</p>

# Provided Attributes

Attribute | Description | Example |
--- | --- | --- | 
Event Name|Event name consisting of magnitude and location name.|M8.6 Indian Ocean|
Latitude|Epicenter latitude value.|2.092430|
Longitude|Epicenter longitude value.|97.152100|
Magnitude|Epicenter magnitude value. Epicenters with magnitudes <5.5 are excluded from the tool. However, epicenters with unknown magnitudes are included.|8.6|
Focal Depth|Epicenter focal depth value. All focal depths are included.|30|
Source|External data source, from where the event information was extracted. ISC-GEM, USGS or NDGC|ISCGEM|
Date|Event date.|28/03/2005|




# Data Sources

Data Source | Link to Data Source | Vintage |
--- | --- | --- | 
NDGC/NCEI| [https://hazard.openquake.org/gem/](https://www.ngdc.noaa.gov/hazard/earthqk.shtml) | 2011 |
ISC-GEM| [https://earthquake.usgs.gov/data/vs30/](https://www.isc.ac.uk/iscgem/overview.php) | June 2024 |
USGS| https://earthquake.usgs.gov/earthquakes/search/| August 2024 |

# User Agreement/Legal Notice

<p align="justify">
The dataset contains data from ISC-GEM, available here: https://www.isc.ac.uk/iscgem/overview.php shared under CC BY-SA 3.0 license.

# Release Date

October 2024
