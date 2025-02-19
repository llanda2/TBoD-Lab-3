# Lab Assignment 3: Interactive World Bank Data Dashboard
**Name: Lauren Landa**

**Professor: Mike Ryu**

**CS-150**
## Overview
This lab focuses on building an interactive dashboard using **Dash** to visualize World Bank data on various indicators. The primary goal is to create a functional and user-friendly interface for exploring global data trends with features such as year selection, data set filtering, and dynamic updates.

## Features
1. **Dynamic Data Visualization**:
   - Select a World Bank indicator and year range to display on a global choropleth map.
2. **Real-Time Updates**:
   - Displays the last date and time the data was fetched in a human-readable format.
3. **Parameter Change Tracking**:
   - Tracks and displays the number of times visualization parameters (e.g., indicator or years) have been updated.
4. **User Interaction**:
   - Adjusts the range of selected years dynamically when the "Submit" button is clicked.

## Components
- **Choropleth Map**: Visualizes the selected indicator data by country.
- **Dropdown Menu**: Allows users to select from multiple indicators.
- **Range Slider**: Enables a range of years for the visualization.
- **Submit Button**: Triggers updates to the map and dynamically adjusts the selected year range.
- **Real-Time Status Updates**:
  - Displays the last update timestamp for the dataset.
  - Tracks the number of times visualization parameters have changed.

## Instructions
1. **Run the Dashboard**:
   - Start the server by running the Python script.
   - Open the provided link (usually `http://127.0.0.1:8050/`) in your web browser.
2. **Select Parameters**:
   - Choose a data set using the dropdown.
   - Adjust the year range with the slider.
3. **Submit and View Updates**:
   - Click the "Submit" button to refresh the visualization.
   - Observe updates to the map, timestamp, and click count.


