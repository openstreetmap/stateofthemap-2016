---
layout: event
title: "SQL all the things: Exposing OSM data services to PostgreSQL users"
theme: techincal
category: technical
name: Jorge Sanz
organization: CARTO
twitter: xurxosanz
osm:
room: b
tags:
  - slot8
youtube_recording: 0PTjHujph-o
---
Accessing Location Data Services through web APIs has been common practice over the last years. When an organization needs to get access to geocoding and routing functionalities they choose a provider, implement their API and integrate that procedure into their business logic, typically building middleware on top of their database. What if we get access to those APIs directly into the database? Imagine a SQL function that get access to a geocoding service backed by OpenStreetMap. Or a another that allows you to generate isochrones for different times and transport methods.

Through the collaboration between CARTO and Mapzen we've built an Open Source Postgres extension to provide a SQL interface for Location Data Services. On this talk we will present the work done at CARTO over the last year to integrate these procedures at the core level of our platform, so users are no longer dependent of a Graphical User Interface to get the best of OSM.
