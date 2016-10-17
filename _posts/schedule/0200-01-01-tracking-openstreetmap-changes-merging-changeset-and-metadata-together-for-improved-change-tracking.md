---
layout: event
title: "Tracking OpenStreetMap changes: Merging changeset and metadata together for improved change tracking"
theme: analysis
category: analysis
name: Dylan Moriarty
organization: Development Seed
twitter: nas_smith
osm:
room: a
tags:
  - slot14
youtube_recording: QA4-eSiDXas
---
Working together with the American Red Cross and the MissingMaps project, we've built a system that tracks user contributions to Missing Maps projects around the globe. Minute by minute it calculates statistics, provides leader boards and awards themed badges for contributions. It's making editing a more social experience.

Tracking changes in OpenStreetMap is difficult but incredibly useful for the community. Tracking changes in real-time requires a pipeline to merge metadata, changeset data, and diff information. This talk will explore the motivation, architecture, and practical implementation of a system. One that reliably handles bursts of data during high periods of activity, yet reduces costs by auto scaling to input as required. We'll talk about how these methods have been implemented using services such as AWS Kinesis and Lambda functions.
