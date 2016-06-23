---
layout: event
title: "Dynamic Timewarp Barycenter Averaging: Repairing Polyline Path Information with User Trajectory Data"
theme: analysis
category: analysis
name: "Matthew Redmond"
organization: "Strava"
twitter:
osm:
room: b
tags:
  - slot19
---
Strava uses OpenStreetMap data throughout our organization. We allow users to create "Strava Segments" - polylines on which run/ride times are compared to other users. When Segments are created with bad data, athletes may receive degraded match results, or a poor visual experience.

We harnessed our collection of GPS trajectory data, a Dynamic Timewarp Barycenter Averaging algorithm to compute consensus sequences, and some standard signal-processing filters to repair inaccurate GPS data with a stronger, data-supported maximum-likelihood estimated path.

This talk is intended for a fairly technical audience, and will dive into the specifics about our repair service and its implementation details.
