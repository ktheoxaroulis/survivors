# Survivors Virus Data Collection Platform

## Overview
The platform consists of 4 parts:
  1. A flutter app (web and mobile) which can be found in /app
  2. A dash-plotly app to analyse collected data (/visualization)
  3. A mongodb which is hosted by mongoDBs Cloud Atlas
  4. A nodejs back-end glueing everything togheter (/server)

## Demo
Visualization of the already collected data can be found here:
 https://survivors-dashboard.herokuapp.com/

The mobile app can not yet be downloaded and thus has to be built locally (follow instructions under /app) but will soon be available in the App Store and Google Play as well.

## Setup
Each part of the platform is hosted in its own repository and can be built independently (follow instructions in sub-repository). To check out the latest release run:
```bash
  git submodule update --init --recursive
```


