# Mapping Waterfalls of Jharkhand Using QGIS

## About the Project

This project is part of my Digital Humanities coursework.

The aim of this project is to map and visualize the geographical distribution of selected waterfalls in Jharkhand, India, using QGIS.

I wanted to explore how geographical information can be represented digitally and how mapping tools can help us understand the distribution of natural heritage sites.

## Objectives

- To identify and map selected waterfalls in Jharkhand.
- To visualize their geographical distribution.
- To learn how geographical data can be collected, filtered, and represented using QGIS.
- To explore the use of digital mapping for documenting natural heritage.

## Tools and Data Used

**QGIS:** Used to import geographical data, manage layers, filter records, and design the map.

**OpenStreetMap:** Source of the waterfall locations and administrative boundary data.

**Overpass Turbo:** Used to extract OpenStreetMap geographical data in GeoJSON format.

**GeoJSON:** File format used to store and import geographical features.

## How I Made This Project

1. I collected waterfall location data for Jharkhand using Overpass Turbo.
2. I downloaded the geographical data in GeoJSON format.
3. I imported the waterfall locations into QGIS.
4. I added the Jharkhand state boundary as a separate layer.
5. I used the attribute table to examine the waterfall records.
6. The original waterfall dataset contained 19 records. I filtered out five records without names, leaving 14 named records.
7. I styled the state boundary and waterfall points using different colours.
8. I added labels to display the names of the waterfalls.

## Current Results

The map displays 14 named OpenStreetMap waterfall records across Jharkhand.

The visualization shows how documented waterfall locations are distributed across different parts of the state.

Two records have similar names, Moti Jharna Falls and Motijharna Falls. These may refer to the same waterfall or different mapped sections and require further verification.

## Limitations

- The dataset is based on OpenStreetMap, which may not contain every waterfall in Jharkhand.
- Some records were excluded from the displayed map because their names were missing.
- Some waterfall names and locations require further verification.
- The map represents selected documented locations rather than a complete inventory of all waterfalls in Jharkhand.

## Digital Humanities Relevance

Digital Humanities uses computational and digital tools to study and represent information.

This project demonstrates how Geographic Information Systems (GIS) can be used to document and visualize natural heritage.

By representing geographical information digitally, the project makes it easier to explore the spatial distribution of documented locations.

## What I Learned

Through this project, I learned how to:

- Work with QGIS for geographical visualization.
- Import GeoJSON datasets.
- Use attribute tables and filters.
- Manage geographical layers.
- Style maps and label locations.
- Recognize the importance of data quality and verification in digital mapping.

## Future Improvements

I plan to extend the project by adding district boundaries and using spatial analysis to count the mapped waterfall locations within each district.

This would help me explore geographical distribution patterns in more detail.

## Data Sources

- [OpenStreetMap](https://www.openstreetmap.org/)
- [Overpass Turbo](https://overpass-turbo.eu/)
- [QGIS](https://qgis.org/)
- [Jharkhand Tourism](https://tourism.jharkhand.gov.in/)

## Project Status

Initial waterfall mapping and visualization completed. Data verification and district-level spatial analysis are planned.
