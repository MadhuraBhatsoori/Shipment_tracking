# Trackonomy Hackathon

## Problem Statement
Critical Pharmaceutical Shipments
The data parameters for monitoring critical pharmaceutical shipments are as follows:

Temperature Range: Must remain between 15°C to 25°C.
Alert through the HTML page if the flight is behind schedule and/or the temperature is reporting outside the range.

Sample Data Files: Example Device 1, Example Device 2, and Example Device 3
Each file includes the starting point and destination point for the shipment. Contains unique latitude and longitude coordinates, temperature readings (°C), and timestamps.

## Solution

### Youtube Demo of Dashboard: https://www.youtube.com/watch?v=6ljW_T06eSg

The web application enables to visualize shipment tracking data with temperature monitoring capabilities. Users upload excel files containing location coordinates and temperature readings, then choose between two visualization options: a map view that plots shipment locations with color-coded temperature indicators (green for the optimal 15-25°C range, red for alerts),  a time-series chart displaying temperature fluctuations over the journey with clear visual indicators of when readings fall outside the acceptable range. 

## Tools and Technology
The frontend uses HTML for structure, CSS for styling and javaScript for functionality. It uses several key libraries: Google Maps API for geographical visualization and heatmap layers, SheetJS (xlsx) for parsing excel data files, and Chart.js adapter for creating interactive time-series visualizations.

