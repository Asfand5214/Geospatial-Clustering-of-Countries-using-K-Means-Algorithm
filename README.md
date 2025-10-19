# Geospatial-Clustering-of-Countries-using-K-Means-Algorithm

# Overview
This project applies **K-Means clustering**, an unsupervised machine learning algorithm, to **group countries based on their geographical coordinates (latitude and longitude). By clustering country centroids, we can identify **regional groupings and spatial patterns** purely from their geographic positions.

The results are displayed on an **interactive world map**, allowing users to visually explore how different countries are grouped into clusters.

The Project is built and executed entirely on **Google Colab**, without the need for any external APIs or dataset downloads beyond a single lightweight GeoJSON file from Natural Earth.

# Objectives
- Extract **latitude** and **longitude coordinates** of countries from a GeoJSON file.
- Apply **K-Means Clustering** to categorize countries into clusters based on geographic location.
- Visualize the clustered countries using **Folium**, an interactive mapping library.
- Demonstrate the integration of **geospatial analysis** and **machine learning** in a simple, offline workflow

# Tools & Libraries
- **Google Colab** - for writing and executing the code
- **GeoPandas** - for geospatial data handling and centroid calculation.
- **scikit-learn** - for implementing K-Means clustering
- **Folium** - for creatig interactive maps
- **Matplotlib** - for cluster distribution visualization

#Methodology 
1. Data Acquisition
2. Data Preprocessing
3. Clustering
4. Visualization

# Results
- Countries were successfully grouped into geographic clusters based on their location coordinates.
- The interactive map clearly highlight **regional similarities**.
- It shows that features like latitude and longitude can reveal meaningful geographic groundings when combined with unsupervised learning.

# How to Run 
1. Open the provided **Google Colab notebook**.
2. Run all cells squentially.
3. The notebook will:
    - Install necessary libraries
    - Load the GeoJSON dataset
    - Compute centroids
    - Perform K-Means clustering
    - Display interactive map and charts
