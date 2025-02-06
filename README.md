# GeoJSON Data Visualization Web Application

## Overview
This project is a web-based application that loads and visualizes geospatial data using **GeoJSON** format. The application asynchronously loads two datasets:
1. **Earthquake Data** (Point data representing recent global earthquakes)
2. **Japan Counties** (Polygon data representing administrative boundaries in Japan)

The application features a **sortable table** displaying earthquake data and an **interactive map** using **Mapbox GL JS**. The map includes earthquake points and Japanese county boundaries with a different map style than the reference `earthquake.html` page.

## Features
- 📍 **Loads and displays GeoJSON data** for earthquakes (points) and Japan counties (polygons).
- 🗺 **Interactive Map** with earthquake points and region overlays.
- 📊 **Sortable Table** to sort earthquake data by location or magnitude.
- 🎨 **Custom Map Style** different from the one used in `earthquake.html`.
- 📏 **Responsive Layout**: The side panel (table) disappears when the viewport width is smaller than `1024px`.

## Repository Structure
