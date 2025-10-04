# meteor-tsunami-visualization
Interactive visualization of meteor impacts and tsunami events with real-time location-based updates. Enter latitude and longitude to view latest meteor &amp; tsunami events with markers, history logs, and status indicators.
# Meteor & Tsunami Visualization Dashboard

## Overview
Interactive map-based visualization showing meteor impacts and tsunami events.

- Enter **latitude and longitude** to mark a location on the map.
- Displays **latest meteor** near the location with crater visualization (red circle).
- Displays **latest tsunami** near the location with polygon visualization (blue polygon).
- Shows **status** of the last meteor and tsunami at the bottom-left.
- Maintains a **history log** of events at the bottom-right.
- Marker updates automatically when inputs are applied.

## Features
- **Top-right vertical input panel** for entering latitude and longitude.
- **Map marker** shows the selected location.
- **Meteor visualization**: red circle representing crater size.
- **Tsunami visualization**: blue polygon showing affected area.
- **Bottom-left status box**: shows last meteor and tsunami events.
- **Bottom-right event log**: lists all nearby events chronologically.
- Automatically **zooms to the selected location**.

## Tech Stack
- HTML, CSS, JavaScript
- [Leaflet.js](https://leafletjs.com/) for interactive maps

## Demo
1. Open `index.html` in your browser.
2. Enter latitude and longitude.
3. Click **Apply Inputs** to see meteor and tsunami events near that location.
