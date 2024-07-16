# Earthquake Visualization Project

## Overview

The United States Geological Survey (USGS) collects extensive data on earthquakes occurring worldwide. This project aims to visualize this data to help educate the public and government organizations about earthquake occurrences, magnitudes, and depths. By providing a meaningful way to display this information, we hope to raise awareness of natural hazards and secure more funding for the USGS.

## Project Structure

This project focuses on creating an earthquake visualization using Leaflet, a JavaScript library for interactive maps.

### Repository Setup

1. **Create a new repository**: Name it `leaflet-challenge`.
2. **Clone the repository**: Clone it to your local machine.
3. **Directory Structure**: Inside your local repository, create the following directories:
   - `Leaflet-Part-1`
   - `Leaflet-Part-2` (optional for additional features)
4. **Add Necessary Files**: Ensure you have the required HTML and JavaScript files. Download the starter code from the provided link: [Starter Code](https://static.bc-edx.com/data/dl-1-2/m15/lms/starter/Starter_Code.zip).
5. **Push Initial Setup to GitHub**: Commit and push the initial setup to GitHub.

### Data Source

The USGS provides earthquake data in various formats, updated every five minutes. For this project, we use the GeoJSON data from the USGS website.

1. **Visit the USGS GeoJSON Feed**: Go to the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page.
2. **Choose a Dataset**: Select a dataset to visualize, such as "All Earthquakes from the Past 7 Days".
3. **Copy the URL**: Use the URL of the chosen JSON data to fetch and visualize the data.

### Visualizing Earthquake Data

Using Leaflet, we create a map that plots all the earthquakes from the dataset based on their longitude and latitude. The visualization includes the following features:

1. **Map Initialization**: Initialize a Leaflet map in the HTML file.
2. **Fetching Data**: Use D3.js to fetch the GeoJSON data from the USGS API.
3. **Plotting Earthquakes**: Plot the earthquakes on the map with markers reflecting the magnitude by size and depth by color.
4. **Legend**: Add a legend to explain the color coding for earthquake depths.
5. **Displaying the Map**: Open your HTML file in a web browser to see the earthquake data visualized on the map.

### Detailed Steps for Visualization

1. **Initialize the Map**:
   - Create a map centered on the United States with an appropriate zoom level.
   - Add a tile layer to the map for the base map imagery.

2. **Fetch and Process Data**:
   - Fetch the earthquake data from the USGS GeoJSON feed using D3.js.
   - Process the data to extract relevant information such as location (latitude and longitude), magnitude, and depth.

3. **Create Markers**:
   - Use circle markers to represent earthquakes.
   - Scale the marker size based on the earthquake magnitude.
   - Color the markers based on the earthquake depth, using a color scale to represent different depth ranges.

4. **Add Popups**:
   - Attach popups to each marker to display additional information about the earthquake, such as its magnitude, location, and depth.

5. **Add a Legend**:
   - Create a legend to explain the color coding for different earthquake depths.
   - Position the legend on the map for easy reference.

### Visualization Output

The following image shows the earthquake data visualized on the map:
![BasicMap](https://github.com/user-attachments/assets/f5548cc4-55a6-4e6a-8301-6e6cf0489b8f)

### Conclusion

By following the steps outlined in this report, you can create a comprehensive earthquake visualization using Leaflet. This visualization helps to better understand earthquake occurrences, their magnitudes, and depths, thereby raising awareness and providing valuable insights for further analysis and decision-making.

### Resources

- **USGS GeoJSON Feed**: [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- **Starter Code**: [Starter Code](https://static.bc-edx.com/data/dl-1-2/m15/lms/starter/Starter_Code.zip)
- **Leaflet Documentation**: [Leaflet](https://leafletjs.com/)
- **D3.js Documentation**: [D3.js](https://d3js.org/)

---

By adhering to the instructions provided, you will successfully create an informative and interactive earthquake visualization that meets the objectives of this project.
