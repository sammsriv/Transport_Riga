# Transport_Riga

## Public Transport Accessibility Analysis of Riga

This project analyzes public transport accessibility in Riga, Latvia using OpenStreetMap data and QGIS.

### Objectives

* Visualize transportation infrastructure in Riga
* Identify public transport stops
* Analyze accessibility using 500-meter walking-distance buffers
* Create maps suitable for urban transport planning studies

### Tools

* QGIS
* OpenStreetMap (Geofabrik)
* GeoPackage (.gpkg)

### Data Source

OpenStreetMap data for Latvia downloaded from Geofabrik.

### Methodology

1. Imported OSM data into QGIS.
2. Classified roads and transportation infrastructure using the `fclass` attribute.
3. Identified bus stops from the transport layer.
4. Generated 500-meter accessibility buffers.
5. Visualized transport coverage and accessibility patterns.

### Results

The analysis shows high public transport accessibility in central Riga and lower accessibility in peripheral areas.

### Repository Structure

* `maps/` – exported map images
* `report/` – project report
* `qgis_project/` – QGIS project files
* `data/` – data source information

### Author

Samriddhi
