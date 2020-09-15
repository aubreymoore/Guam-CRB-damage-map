# Guam-CRB-damage-map

This repo contains the most recent version of an interactive web map of coconut rhinoceros beetle damage on Guam.
Data are from a roadside video survey. The map can be viewed at https://aubreymoore.github.io/Guam-CRB-damage-map/.

Layers are stored in the **spatialite** database named **videosurvey.db**. 

To regenerate the map:

* Clone this repo.
* Install QGIS 3.14 or later.
* Install the **qgis2web** QGIS plugin.
* Run the python script. You can do this from the command line using:
```
qgis --codepath make_crb_damage_map.py
```
