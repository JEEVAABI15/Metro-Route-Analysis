# Metro Network Analysis

This project focuses on visualizing and analyzing the Metro network using **Python**, **Pandas**, **Folium**, and **Plotly**. The dataset used includes information about metro lines, station names, geographic locations, and opening dates.

## Features

- **Data Preprocessing**:
  - Checked for missing values and verified data types.
  - Converted the 'Opening Date' to a `datetime` format.
  - Added a new column 'Opening Year' for time-based analysis of metro expansion.

- **Geospatial Visualization**:
  - Utilized the **Folium** library to create an interactive map of Metro stations.
  - Each station is marked with a colored marker corresponding to the metro line, with tooltips showing station names and line details.

- **Annual Station Growth**:
  - Visualized the number of metro stations opened each year using **Plotly Express** bar charts.
  - Analyzed the expansion of the metro network over time, showing trends in station openings.

- **Metro Line Analysis**:
  - Analyzed the number of stations per metro line and calculated the average distance between stations.
  - Created a two-part subplot using **Plotly** to compare:
    - The number of stations per metro line.
    - The average distance between stations for each metro line.

- **Station Layout Distribution**:
  - Examined the distribution of station layouts (such as Elevated, Underground, etc.) across the network.
  - Visualized the layout distribution using **Plotly** bar charts, with customized colors and labels for clear presentation.

## Visualizations

1. **Metro Map**: An interactive map of all Delhi Metro stations, color-coded by line.
2. **Station Openings per Year**: A bar chart showing the number of stations opened each year.
3. **Metro Line Analysis**: A subplot comparing the number of stations and average distance between stations for each metro line.
4. **Station Layout Distribution**: A bar chart displaying the number of stations per layout type.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **Folium**: For creating interactive maps of metro stations.
- **Plotly**: For creating visualizations (bar charts and subplots).
- **Plotly Express**: For simple and easy-to-use charting.

## Dataset

The dataset used for this project contains the following columns:

- **Station Name**: Name of the metro station.
- **Line**: The metro line the station belongs to.
- **Latitude**: Latitude coordinate of the station.
- **Longitude**: Longitude coordinate of the station.
- **Distance from Start (km)**: Distance of the station from the start of the line.
- **Opening Date**: Date when the station was opened.
- **Station Layout**: Layout type of the station (Elevated, Underground, etc.).

## Future Work

- Add analysis on ridership data.
- Implement time-series forecasting on metro station openings.
- Extend the project to other metro networks in India.

## How to Run

1. Install required libraries:
   ```bash
   pip install pandas folium plotly
