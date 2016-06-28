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
This is a talk about a project called “Trending Places on OpenStreetMap”. The goal of this project is to find significant viewing activity worldwide on the main web map (“slippy map”) of OpenStreetMap (OSM). This activity may be indicative of popular news or events in that region.

A web map consists of map tiles at different zoom levels. The views of these tiles are logged daily and published in an anonymized form with a delay of 2 days. For previous 7 days this log is aggregated up to zoom level 14 and a so called T-score is calculated to standardize the data. Values above a certain threshold are filtered out to catch spikes. These spikes are ranked relative to the mean increase in views overall. Some places in this ranking might be close to each other, so they are clustered.

Finally, the tile coordinates are reverse geocoded in order to get geographic names. A Twitter bot called @trending_places tweets once a day about these top 10 trending places.
