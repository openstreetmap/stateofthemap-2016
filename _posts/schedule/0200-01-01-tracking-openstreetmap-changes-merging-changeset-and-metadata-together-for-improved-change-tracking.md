---
layout: event
title: Tracking OpenStreetMap changes. Merging changeset and metadata together for improved change tracking
theme: analysis
category: analysis
name: Nate Smith
organization: Development Seed
twitter: nas_smith
osm:
room: a
tags:
  - slot14
---
Working together with the American Red Cross and the MissingMaps project, we've built a change tracking pipeline that tracks user trends in real-time and rewards contributors for their efforts. The pipeline ingests and processes, minute by minute, the user commits for Missing Maps projects around the globe. Calculating statistics and providing leaderboards and awarding themed badges for contributions provide a more social experience.

Tracking changes in OpenStreetMap is difficult but incredibly useful for the community. Replication files contain one set of information while other files store another set of information. Augmented diffs extend the minutely diffs but are generated outside of the core OSM infrastructure. Tracking changes in real-time requires a pipeline to merge metadata, changeset data, and diff information.

This talk will explore the motivation, architecture, and practical implementation of a system that needs to be able to reliably handle bursts of data during high periods of activity, yet reducing costs by auto scaling to input as required. We'll talk about how these methods have been implemented using services such as AWS Kinesis and Lambda functions.
