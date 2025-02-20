<!-- [![GitHub tag](https://img.shields.io/github/v/tag/gboeing/osmnx-examples?label=Uses+OSMnx)](https://github.com/gboeing/osmnx)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gboeing/osmnx-examples/main?urlpath=lab)
[![Build Status](https://github.com/gboeing/osmnx-examples/workflows/tests/badge.svg?branch=main)](https://github.com/gboeing/osmnx-examples/actions?query=workflow%3Atests) -->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fjrodl/self-air-routes.git/HEAD)

# SELF-AIR Route Calculation

Efficient route planning is fundamental for improving the navigation capabilities of quadruped robots in diverse and challenging terrains. This repository focuses on identifying and extracting optimal routes while considering terrain variability, ensuring adaptability to the robot's autonomy, and minimizing travel distances.

A key aspect of this work is integrating geospatial data to enhance path calculation. To demonstrate these capabilities, this repository presents a case study conducted in Tabuyo del Monte, leveraging QGIS-extracted data for route optimization. The approach aims to provide a more robust and adaptable navigation framework, essential for real-world applications in agriculture, wildlife monitoring, and autonomous exploration.

The demo showcases how terrain analysis, GIS-based route extraction, and adaptive path planning contribute to the autonomous mobility of quadruped robots.

## Try It Online 🚀

You can test this project interactively using Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fjrodl/self-air-routes.git/HEAD)


## Reference/Source Repository

#### OSMnx Examples Gallery

OSMnx 2.0 is coming soon: read the [migration guide](https://github.com/gboeing/osmnx/issues/1123).

[OSMnx](https://github.com/gboeing/osmnx) is a Python package to download, model, analyze, and visualize street networks and other geospatial features from [OpenStreetMap](https://www.openstreetmap.org/copyright/). You can download and model walking, driving, or biking networks with a single line of code then easily analyze and visualize them. You can just as easily work with urban amenities/points of interest, building footprints, transit stops, elevation data, street orientations, speed/travel time, and routing.

This gallery contains step-by-step usage tutorials and feature demonstrations as Jupyter notebooks. You can run these notebooks interactively online with [Binder](https://mybinder.org/v2/gh/gboeing/osmnx-examples/main?urlpath=lab) or locally with the official OSMnx [Docker image](https://hub.docker.com/r/gboeing/osmnx). All of the examples are in this repo's [notebooks](notebooks) folder. Note that this repo's main branch generally tracks the functionality of the OSMnx repo's main branch. For examples corresponding to previously released versions of OSMnx, use this repo's tags to browse by release.

#### More info:

- [Overview of OSMnx](https://geoffboeing.com/2016/11/osmnx-python-street-networks/)
- [OSMnx repo](https://github.com/gboeing/osmnx)
- [Documentation](https://osmnx.readthedocs.io/)
- [Journal article and citation info](https://geoffboeing.com/publications/osmnx-complex-street-networks/)

## Acknowledgment: SELF-AIR Project

Supporting Extensive Livestock Farming with the use of Autonomous Intelligent Robots 

<img src="https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/robotics_wolf_minimal.png" alt= "SELF_AIR_logo" width="50%" height="50%">

Grant TED2021-132356B-I00 funded by MCIN/AEI/10.13039/501100011033 and by the “European Union NextGenerationEU/PRTR"

![SELF_AIR_EU eu_logo](https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/micin-financiadoUEnextgeneration-prtr-aei.png)
