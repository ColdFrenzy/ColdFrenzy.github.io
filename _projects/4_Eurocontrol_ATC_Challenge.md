---
layout: page
title: ATC challenge
description: reinforcement learning for collision avoidance in multi_UAV systems
img: assets/img/atc_challenge/Eurocontrol_logo.jpg
importance: 1
category: work
---

<h1>Overview</h1>
<a href="https://github.com/ColdFrenzy/atcenv/tree/805750172b199f7092493bfb436f878b1785ebc2">code</a>

For this challenge, EUROCONTROL provided an Air Traffic Control (ATC) environment based on the 
<a href="https://shapely.readthedocs.io/en/stable/manual.html">shapely</a> library.
In its basic form, the environment generates an Airspace, which corresponds to a 2D convex polygon and starting and target points situated on the edges of the polygon for each UAV.

The goal was to define custom actions, states/observations and rewards and a reinforcement learning solution for the conflict resolution problem.

