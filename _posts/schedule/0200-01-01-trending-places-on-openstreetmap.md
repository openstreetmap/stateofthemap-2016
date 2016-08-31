---
layout: event
title: Trending Places on OpenStreetMap
theme: analysis
category: analysis
name: Stefan Keller
organization: Geometa Lab at HSR, Univ. of Applied Sciences Rapperswil
twitter: sfkeller
osm:
room: a
tags:
  - slot12
---
Current news or a popular event in a region may result in a increase in map views. The goal of “Trending Places on OpenStreetMap” is to locate where there is a high viewing activity occurs on the main OpenStreetMap web map. The map consists of many tiles and the views of these tiles are logged daily and following processing the top trending places are tweeted by @trending_places. 

Stefan describes the process: For previous 7 days the tile view log is aggregated up to zoom level 14 and a so called T-score is calculated to standardize the data. Values above a certain threshold are filtered out to catch spikes and these are then ranked relative to the mean increase in views overall. Clustering eliminates locations that are near one another. Finally, the tile coordinates are reverse geocoded in order to get geographic names and a Twitter bot announces the top 10.
