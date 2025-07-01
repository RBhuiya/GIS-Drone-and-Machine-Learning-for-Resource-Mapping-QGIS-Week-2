# 🌏📗 GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-2 🗾
# 🇮🇳 QGIS India's Geospatial Data Project
This project focuses on building an interactive GIS (Geographic Information System) map that allows users to visualize, explore, and analyze state-level and district-level administrative boundaries using spatial data.
By leveraging vector layers (state & district boundaries), raster imagery (satellite bands), and geolocation coordinates, the project aims to provide a foundation for spatial analysis, zoning studies, and area-specific insights—starting with a detailed focus on Gujarat, India.
Whether for urban planning, agriculture, or infrastructure development, this map acts as a powerful tool for understanding geographic patterns and making data-driven decisions.
![A-2-1](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-2/blob/c566de441589bad2aabb6208e7e706395776de9a/Screenshort/A-2-1.png)

# 🔎 Project Overview
This project is a GIS-based mapping system designed to visualize and analyze administrative boundaries and spatial data layers for Indian states and districts. It combines vector data (such as state and district boundaries) with raster data (like satellite imagery using Bands 1, 2, 3) to build an interactive and informative map interface.

# 🗝️ Key Features:
-Visualization of state and district boundaries with layered control
-Integration of raster data for enhanced geographic context
-Use of real coordinates to pinpoint specific zones or regions
-Focused spatial exploration of Gujarat, with internal boundary mapping
-Scalable structure to support additional states and datasets

# 🎯 Objective
The primary objective of this project is to develop an interactive GIS-based platform that enables users to:
-✅ Visualize administrative boundaries at both state and district levels
-✅ Integrate and display raster data (Bands 1, 2, 3) for detailed geographical insights
-✅ Utilize real-world coordinates to focus on specific zones or areas of interest
-✅ Enable internal boundary mapping for in-depth analysis of selected states (starting with Gujarat)
-✅ Lay the foundation for scalable spatial analysis applicable across various sectors like urban planning, agriculture, disaster response, and infrastructure development
By achieving these goals, the project aims to bridge raw geospatial data with meaningful, visual insights for decision-making and regional planning.

# 🛠️ Project Steps
Below are the key steps followed in this project to build an interactive and layered GIS mapping system:
1. Initial Setup
  -Installed necessary GIS tools and libraries (e.g., QGIS, Leaflet, Python libraries like Geopandas, Rasterio).
  -Set up project directory and organized datasets (vector and raster).

2. Adding Base Layers
  -Loaded the state boundary layer as the base layer.
  -Verified geometries and corrected any inconsistencies in shapefiles.

3. Overlaying District Layers
  -Added and visualized district-level shapefiles on top of the state layer.
  -Styled districts with unique colors and borders for clear distinction.

4. Raster Data Integration
  -Imported raster datasets (e.g., satellite images or remote sensing data).
  -Enabled Band 1, 2, 3 (RGB composite) for enhanced visual analysis.
  -Aligned raster data accurately with vector layers using proper projections.

5. Geolocation and Coordinate Mapping
  -Integrated functionality to input and navigate using real-world coordinates.
  -Enabled focused zoom on specific regions/zones based on coordinates.

6. Focus on Gujarat
  -Zoomed into Gujarat state for deeper analysis.
  -Activated internal district boundaries to visualize administrative divisions.
  -Prepared the map for detailed region-specific spatial study.

7. Layer Management
  -Implemented controls for layer visibility, transparency, and interaction.
  -Ensured smooth toggling between base layers, district overlays, and raster images.

8. Map Export/Save (Optional)
  -Enabled export of custom views or saved layer configurations for reporting or sharing.

# 🖥️ Screenshot
- (On Layers Selecting -> Districts -> TN2 ✅ -> AP-1 ✅ & State Layer)

  -![A-2-1](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-2/blob/c566de441589bad2aabb6208e7e706395776de9a/Screenshort/A-2-1.png)
- (Adding Layer TN with Band-1,2,3)

  -![A-2-2](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-2/blob/c566de441589bad2aabb6208e7e706395776de9a/Screenshort/A-2-2.jpg)

- (Here we are changing the brush colour to non -> And exploring the state boundaries)
  -![A-2-3](https://github.com/RBhuiya/GIS-Drone-and-Machine-Learning-for-Resource-Mapping-QGIS-Week-2/blob/c566de441589bad2aabb6208e7e706395776de9a/Screenshort/A-2-3.jpg)

# 📝 Requirements
- ⬇️ Install QGIS: [official website](https://qgis.org/download/) (latest version).
- 🟢 Getting Started:
   1.	Clone this repository to your local machine: 
   2.	Open QGIS, and load the states.shp and districts.shp file located in the Main (Source Data File) folder.
   3.	Explore the data:
        - View district boundaries on the map.
        - Use QGIS query tools to view district codes and states.
        - Utilize QGIS analysis tools to study district borders and how they share boundaries with neighboring districts or states.

# ✅️ Benefits of This Analysis
By working with this dataset, users can:
   - Quickly identify which district is located in which state.
   - Analyse how much boundary each district shares with others.
   - Gain insights into administrative divisions and border-sharing relationships, which could be useful for policymaking, resource distribution, and regional planning.

# 👨‍💼Author
Mr. Rahul Bhuiya | 4th year CSE-AIML student at MCKVIE'26🎓
