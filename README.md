# Qgis-earthengine-Fires-Monitoring

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<figure><img src='img\S_2_fires.png' alt='Forest Fires in Honduras, April 2020. Image: Copernicus.' style="align:center; width:100%;"></img><figcaption>Forest Fires in Honduras. Image: ESA.</figcaption><figure>
<hr>
  
## 1. Description

The following is a Python example of the [Google Earth Engine plugin for QGIS](https://github.com/gee-community/qgis-earthengine-plugin), for monitoring and tracking wildfires on  the Google Earth Engine [API Documentation](https://developers.google.com/earth-engine/). This script were adapted from [Google Earth Engine plugin](https://github.com/gee-community/qgis-earthengine-plugin/tree/master/examples) and the Earth Engine [API examples](https://github.com/google/earthengine-api/tree/master/python/examples). In addition, it includes some examples adapted from the examples developed as recommended practices of the [UNSPIDER](https://www.un-spider.org) (oficina de Bonn -Alemania) program.

## 2. Steps

* **Step 1:** [Sign up](https://earthengine.google.com/signup/) for [Google Earth Engine](https://earthengine.google.com/).
* **Step 2:** Install [QGIS](https://qgis.org/).
* **Step 3:** Install the [Google Earth Engine Plugin for QGIS](https://gee-community.github.io/qgis-earthengine-plugin/) and authenticate Google Earth Engine.
* **Step 4:** Git clone or [download](https://github.com/giswqs/qgis-earthengine-examples/archive/master.zip) this repository.
* **Step 5:** Open the Python console in QGIS and load any downloaded Python script into the QGIS Python Editor.
* **Step 6:** Click the *Run script* button on the Python Editor to execute the script.
* **Step 7:** Zoom in/out the QGIS Canvas to inspect the results.

## 2. Install

We install the Google Earth Engine plugin for QGIS. To do this we must go to the top menu of QGIS and click on **Add-ons> Manage and install add-ons ...** In the search box we type "Google Earth", select the plugin and install it.
<figure><img src='img\gee_QGIS.png' alt='GEE plugin' style="align:center; width:100%;"></img><figcaption> GEE Plugin</figcaption><figure>
<hr>

## 3. Add QGIS Basemaps

* Open the Python console in QGIS and load the Python script ([Basemaps/qgis_basemaps.py](https://github.com/Alexanderariza/qgis-earthengine-Fires-Monitoring/blob/master/Python/Base_maps.py)) into the QGIS Python Editor.
* Click the *Run script* button on the Python Editor to execute the script. This will add many basesmaps as XYZ tiles to QGIS. Select and double click any basemap under XYZ Ttiles to be added to QGIS Canvas. See the screenshot below.
* Alternatively, you can install the QGIS [QuickMapServices](https://plugins.qgis.org/plugins/quick_map_services/) plugin. After installing the plugin, go to _QGIS_ -- _Web_ --_QuickMapServices_ -- _Settings_ -- _More services_ -- _Get contributed pack_ -- _Save_. 

![QGIS Basemaps](https://github.com/Alexanderariza/qgis-earthengine-Fires-Monitoring/blob/master/img/qgis_gee_3.png)

## 4. Run Earth Engine on QGIS (Plugin) 

![qgis-gee-demo](https://github.com/Alexanderariza/qgis-earthengine-Fires-Monitoring/blob/master/img/strm_basem.gif)


