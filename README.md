# Kentucky River Watershed Watch
### Interactive Water Quality Map

## Project Overview

This project is an interactive web map displaying water quality measurements collected across Kentucky through Kentucky River Watershed Watch.

The map was developed using HTML, CSS, JavaScript, and Leaflet.js. It allows users to explore the spatial distribution of four water quality parameters:

- E. coli
- pH
- Dissolved Oxygen
- Water Temperature

The purpose of this map is to visualize water quality conditions across different monitoring locations and provide an accessible way to explore environmental data.

## Map Features

### Interactive Mapping
- Users can switch between four water quality datasets.
- Monitoring locations are represented by proportional circles.
- Hovering over circles highlights individual sampling locations and displays measurement values.
- Clicking a circle displays available water quality measurements.
- A dynamic legend provides information about the selected parameter.

### Proportional Circle Symbology

Circle sizes are determined by the measured value at each sampling location.

Larger circles represent higher measured values, while smaller circles represent lower measured values.

The map uses square-root scaling, following the proportional symbol mapping method demonstrated in class.

Square-root scaling allows circle areas to increase proportionally with the data values before minimum and maximum radius limits are applied.

## Data

**Source:** Kentucky River Watershed Watch
The dataset contains water quality sampling records with geographic coordinates and environmental measurements.

Parameters include:

- **E. coli:** Indicator of fecal contamination in surface water.
- **pH:** Measurement of water acidity or alkalinity.
- **Dissolved Oxygen:** Concentration of oxygen available to aquatic organisms.
- **Temperature:** Water temperature, which influences aquatic ecosystems and dissolved oxygen availability.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Leaflet.js
- GeoJSON
- OpenStreetMap

## Map Interpretation

Circle size represents the magnitude of the selected water quality measurement.

Circle color represents the measurement category defined in the map's legend.

Users can select different parameters to compare spatial patterns across monitoring locations.

Larger circles do not necessarily indicate poorer water quality. Interpretation depends on the selected parameter.

## Limitations

- Some monitoring locations may have missing measurements.
- Multiple sampling records may occur at the same location.
- Circle sizes are limited by minimum and maximum radius settings.
- Water quality measurements may represent different sampling dates.
- Map classifications are illustrative and should not automatically be interpreted as regulatory water quality standards.

## Credits

**Map Author:** Vicky Apostolides

**Data Source:** Kentucky River Watershed Watch

**Mapping Library:** Leaflet.js

**Basemap:** OpenStreetMap

**Course Project:** Interactive Web Mapping
