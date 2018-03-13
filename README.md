# bertt/wmts

Collection of WMTS services. 

## Maps

Apple, Carto, Gaode, Google, IsHowChina, Kosmosnimki, MapBox, MapSurfer, Michelin, Nokia, Stamen, Strava, Taobao, Tencent, ThunderForest, Tianditu, TomTom, VWorld, Yandex

Note about Strava: There are several files for Strava heatmaps supporting the colors:

Gold layers (default): https://bertt.github.io/wmts/capabilities/strava.xml

Blue layers: https://bertt.github.io/wmts/capabilities/strava-blue.xml

Gray layers: https://bertt.github.io/wmts/capabilities/strava-gray.xml

Bluered layers: https://bertt.github.io/wmts/capabilities/strava-bluered.xml

strava2017.xml is deprecated and will be removed later on.

## Instructions
Sample viewer see <a href="https://bertt.github.io/wmts/">https://bertt.github.io/wmts/</a>

For other applications: 

Sample retrieving capabilities files on github.io:

```
$ curl https://bertt.github.io/wmts/capabilities/mapbox.xml
```

QGIS Instructions:

Browser panel -> WMS -> New Connection

<img src="add-connection.png">

Select layer

<img src="add-layer.png">



