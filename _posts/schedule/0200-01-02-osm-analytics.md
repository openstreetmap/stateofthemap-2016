---
layout: event
title: "OpenStreetMap Analytics: Rewarding contributors by tracking OpenStreetMap in real-time"
theme: analysis
category: analysis
name: "Marc Farra"
organization: "Development Seed"
twitter:
osm:
room: b
tags:
  - slot21
---

Mapathons are an increasingly effective way to get data into OpenStreetMap. The Missing Maps project hosts mapathons to increase the amount of data in areas that don't have large local OpenStreetMap communities.

Using the OpenStreetMap tasking manager and data from Missing Maps, the American Red Cross built an analytics platform that tracks user trends in real-time and rewards contributors for their efforts. This creates an augmented dataset of a user's activity, consistency and relative reputation. User feedback is provided in detailed metrics as well as rewarded with a variety of themed badges based on the type and magnitude of contributions. Badges range from simple tasks (""Add 4 roads"") to challenging to obtain (""Map in 10 countries""). Leaderboard pages display up to date detail on the most active users for a current project, while hashtag groupings display statistics to be separated out, allowing tracking of groups.

The system consists of a pipeline that ingests and processes the minute by minute tracking of user commits for Missing Maps projects around the globe. This talk will explore the motivation, architecture, and practical implementation of a system that needs to be able to reliably handle bursts of data during high periods of activity, yet reducing costs by auto scaling to input as required.
