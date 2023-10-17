# Earthquake Analysis Introduction

Thank you for visiting this repository which holds data and code for analyzing earthquakes in the Los Angeles area from 1970 to 2023. The project was created to satisfy the requirements of a graduate-level course in Applied Data Science for Business. The collaborators are:
* Justin Farnan jfarnan@sandiego.edu
* Stephen Reagin sreagin@sandiego.edu

## Problem Statement

Earthquakes are a natural seismic phenomenon characterized by a moving and shaking of the ground. They range in size from mild tremors to violent destruction of large geographies, and they can be modeled as waves with amplitudes traveling across the Earth’s surface.

Earthquake events are recorded by seismometer instruments designed to measure the shaking of the ground. A sufficient array of seismometers across a large area can help triangulate the location, size, and timing of earthquakes.

A major earthquake has never been predicted by a scientific model. Because of their unpredictable nature and potential for catastrophic damage, seismologists and insurance actuaries use statistical analysis to assess the probability of a major earthquake event occurring in a given location over a specified period of time


## Dataset
Data comes from the United States Geological Survey libcomcat library: https://code.usgs.gov/ghsc/esi/libcomcat-python

The initial dataset consists of [xyz] earthquake records covering a 150km radius centered around Los Angeles.

## Results

We are able to forecast 5 years of future earthquakes for 10 of the 441 grid points

We have a model that is somewhat accurate in “predicting” past events, however more research needs to be done

Our current systems cannot handle the compute to run all 441 grid points

With the proper tools and technology along with hiring more experts in this space, we are confident we can get a model that is fairly accurate
