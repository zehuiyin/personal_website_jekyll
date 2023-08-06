---
title:  "Toronto Transit Commission Real Time Web Map"
mathjax: true
layout: post
---

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="Bikeshare_Web_Map" src="https://zehuiyin.github.io/toronto_bikeshare_station_info/"></iframe></div>
<p style="margin-bottom:0.8cm;"></p>

This web map shows the latest information about the bikeshare Toronto stations, such as their address and capacity. 

<!-- readmore -->

The data comes from the [GBFS](https://tor.publicbikesystem.net/ube/gbfs/v1/en/station_information), a public API that provides standardized bike-sharing information. The map does not have an auto-refresh feature, because the API does not update very often. However, you can refresh the web page manually to get the most current data from the API. To access the web map, please click on this [link](https://zehuiyin.github.io/toronto_bikeshare_station_info/). You can zoom in and out, pan around, and click on the bus markers to see more information in pop-ups.

Created by Zehui Yin with <i>MapLibre GL JS</i> and <i>Maptiler</i>.
