# Project Blueprint

## Overview

This project is a real-time Iran Tension Monitor dashboard. It provides a live feed of information related to the geopolitical situation in Iran, including military asset tracking, news updates, market data, and risk analysis.

## Implemented Features

### Design and Layout

*   **Dark Theme:** A dark, modern UI suitable for a command-center-style dashboard.
*   **Three-Column Layout:**
    *   **Left Sidebar:** Displays risk index, live asset counts, market data, and data source status.
    *   **Center Panel:** A map of the region on the top half and a live news stream on the bottom half.
    *   **Right Sidebar:** Contains tabbed panes for OSINT (Open Source Intelligence) from X (formerly Twitter), Polymarket prediction markets, the "Pizza Index," Key Risk Indicators (KRIs), and scenario analysis.
*   **Responsive Elements:** The sidebars are collapsible to maximize the center panel view.
*   **Header:** Displays the application title, a "LIVE" badge, a real-time UTC clock, and a ticker for important alerts.
*   **Bottom Ticker:** A scrolling ticker at the bottom of the page showing key market data and other indicators.

### Core Features

*   **Live Map:** An interactive map powered by Leaflet.js, showing:
    *   Military aircraft with clustering for better visualization.
    *   Naval assets, including US aircraft carriers.
    *   Military bases in the region.
    *   Range circles for different assets.
*   **Live News Stream:** A continuously updating feed of news from various sources.
*   **Aircraft Tracking:**
    *   Simulated real-time tracking of military aircraft.
    *   Filtering of aircraft by type and speed.
*   **Risk Analysis:**
    *   A "Risk Index" with a visual gauge.
    *   Signal strength indicators for various data sources.
*   **OSINT Feed:** A simulated feed of X posts from OSINT accounts.
*   **Prediction Markets:** A display of data from prediction markets like Polymarket.
*   **Pizza Index:** A whimsical but illustrative data point tracking pizza orders near the Pentagon as a leading indicator.
*   **Key Risk Indicators (KRIs):** A list of key indicators with their current status.
*   **Scenario Analysis:** A Monte Carlo simulation of potential scenarios.

### Interactivity

*   **Sound and TTS:** Toggleable sound effects and text-to-speech for alerts.
*   **Interactive Map:** Clickable markers with pop-up information.
*   **News Popup:** A modal window to view the full details of a news story.
*   **Collapsible Sidebars:** Users can collapse the sidebars to focus on the map and news feed.
*   **Filtering:** Users can filter the displayed aircraft on the map.
*   **Manual Scan:** A button to trigger a manual scan for new data.

### Technical Implementation

*   **HTML:** A single `index.html` file provides the structure of the application.
*   **CSS:** A single `<style>` block within the HTML file contains all the styling for the application. It uses modern CSS features like custom properties (variables) for theming.
*   **JavaScript:** A single `<script>` block within the HTML file contains all the application logic, including:
    *   WebSocket connection for receiving live data.
    *   Map initialization and updates using Leaflet.js and Leaflet.markercluster.
    *   DOM manipulation for updating the UI with new data.
    *   Audio and TTS playback.
    *   Simulated data fetching and updates.
*   **Libraries:**
    *   **Leaflet.js:** For the interactive map.
    *   **Leaflet.markercluster:** For clustering markers on the map.

## Current Plan

The user has requested to implement the provided HTML content. The `index.html` file has been updated with this content. All features described above are now implemented in the `index.html` file.
