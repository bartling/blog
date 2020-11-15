---
title: Evanston Elections
author: ''
date: '2020-11-15'
slug: []
categories:
  - R
  - GIS
tags: []
featuredImg: ''
---
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/htmlwidgets-1.5.2/htmlwidgets.js"></script>
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/jquery-1.12.4/jquery.min.js"></script>
<link href="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/leaflet-1.3.1/leaflet.css" rel="stylesheet" />
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/leaflet-1.3.1/leaflet.js"></script>
<link href="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/leafletfix-1.0.0/leafletfix.css" rel="stylesheet" />
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/Proj4Leaflet-1.0.1/proj4-compressed.js"></script>
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/Proj4Leaflet-1.0.1/proj4leaflet.js"></script>
<link href="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/rstudio_leaflet-1.3.1/rstudio_leaflet.css" rel="stylesheet" />
<script src="{{< relref "posts/2020-11-15-evanston-elections/index.markdown" >}}index_files/leaflet-binding-2.0.3/leaflet.js"></script>

Test


```r
library(leaflet)
m <- leaflet() %>%
  addTiles() %>%  # Add default OpenStreetMap map tiles
  addMarkers(lng=174.768, lat=-36.852, popup="The birthplace of R")
m  # Print the map
```

<div id="htmlwidget-1" style="width:672px;height:480px;" class="leaflet html-widget"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}}},"calls":[{"method":"addTiles","args":["//{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false,"attribution":"&copy; <a href=\"http://openstreetmap.org\">OpenStreetMap<\/a> contributors, <a href=\"http://creativecommons.org/licenses/by-sa/2.0/\">CC-BY-SA<\/a>"}]},{"method":"addMarkers","args":[-36.852,174.768,null,null,null,{"interactive":true,"draggable":false,"keyboard":true,"title":"","alt":"","zIndexOffset":0,"opacity":1,"riseOnHover":false,"riseOffset":250},"The birthplace of R",null,null,null,null,{"interactive":false,"permanent":false,"direction":"auto","opacity":1,"offset":[0,0],"textsize":"10px","textOnly":false,"className":"","sticky":true},null]}],"limits":{"lat":[-36.852,-36.852],"lng":[174.768,174.768]}},"evals":[],"jsHooks":[]}</script>

