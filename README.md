# Urban Tree Density and Environmental Impact: Analyzing Temperature Regulation and Oxygen Production

## Project Overview
This repository contains the analysis and visualization code for understanding the relationship between tree density, temperature regulation, and oxygen production in Berlin. Using open-source data, this project explores the role of urban trees in mitigating heat and improving air quality, offering insights into how greenery can shape a more sustainable urban environment.

**Key Outcomes**:
- **Tree Data**: 885,825 trees mapped from Berlin’s public dataset.
- **Temperature Regulation**: High-density tree areas showed up to 1.48°C lower temperatures.
- **Oxygen Production**: Estimated based on biomass using allometric equations.
- **Public Engagement**: Interactive models allow residents to visualize tree benefits in their neighborhoods.

## File Descriptions

### Jupyter Notebooks

1. **Analyzing and Visualizing the Relation Between the Normalized Temperature Stability Index and Temperature Data.ipynb**
   - **Purpose**: This notebook explores the correlation between the Normalized Temperature Stability Index (NTSI) and temperature variations in different parts of Berlin.
   - **How to Use**: Replace the input dataset paths as indicated in the code cells to adapt the analysis to different regions.

2. **Analyzing and Visualizing the Relation Between Different Categories of Tree Densities and Temperature Data.ipynb**
   - **Purpose**: This notebook analyzes the temperature changes across areas categorized by tree density (low, medium, and high) in Berlin.
   - **How to Use**: Replace the input data where indicated to apply this to different regions or datasets.

3. **Visualizing the Mean Temperature (Celsius) Versus the Number of Trees for All Four Months.ipynb**
   - **Purpose**: This notebook visualizes the relationship between the number of trees and average temperature in summer months (June to September).
   - **How to Use**: Modify the input data paths as instructed to customize this analysis.

### QGIS Project Files

1. **How Much Cooler Did Trees Make It for Me.qgz**
   - **Purpose**: A QGIS project file visualizing the impact of tree density on temperature regulation throughout Berlin. The file maps tree density and correlates it with temperature data.
   - **How to Use**: Open the .qgz file in QGIS to explore the spatial analysis of tree density and cooling effects.

2. **How Much Oxygen Did Trees Give Me.qgz**
   - **Purpose**: A QGIS project file mapping oxygen production based on tree density and biomass. The analysis calculates annual oxygen production using allometric equations.
   - **How to Use**: Open the .qgz file in QGIS to visualize how tree density influences oxygen output.

## Methodology

The project relies on publicly available data, processed through Python scripts and spatial analysis software. Here’s a breakdown of the key steps involved:

1. **Data Collection**:
   - Tree data from Berlin’s Geoportal FIS Broker, mapped for 885,825 trees.
   - Hourly temperature data for Berlin during the summer months (June–September).

2. **Analysis**:
   - **Temperature Regulation**: Evaluated using the Normalized Temperature Stability Index and categorized by tree density.
   - **Oxygen Production**: Estimated through allometric equations to calculate biomass and oxygen output.

3. **Interactive Public Engagement**:
   - QGIS models allow the public to explore tree density’s environmental impact in their neighborhoods.

