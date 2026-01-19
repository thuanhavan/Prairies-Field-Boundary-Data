# Prairies-Field-Boundary-Data
Field boundary of the Canadian Prairies for downloading
Prairies Field Boundary Data

<img width="1232" height="590" alt="image" src="https://github.com/user-attachments/assets/e2c682b6-8639-46d4-bdb9-00b22052e5b4" />

Overview

This repository documents and links to the Prairies Field Boundary Dataset, a large-scale geospatial dataset of agricultural field boundaries across the Canadian Prairies derived from Sentinel-2 imagery using the Segment Anything Model (SAM v2). The dataset provides polygon representations of cultivated fields suitable for regional to continental-scale agricultural and environmental analyses.

The data support applications in precision agriculture, land-use mapping, crop monitoring, yield modelling, and integration with multi-source geospatial data cubes.

Specifications Table
Item	Description
Subject	Earth & Environmental Sciences
Specific subject area	Agricultural field boundary mapping using satellite imagery and automated image segmentation for large-scale cropland analysis
Type of data	Geospatial polygon data (Shapefile, GeoParquet)
Data collection	Multispectral Sentinel-2 surface reflectance imagery accessed via Google Earth Engine (GEE). Seasonal Red–Green–Blue composites representing key crop phenological stages were generated and used as input to the Segment Anything Model (SAM) for automated field boundary segmentation without manual labelling. Segmentation masks were filtered to remove non-cropland artifacts, vectorized into polygon features, and topologically cleaned to ensure spatial consistency. All processing was conducted using Python-based geospatial workflows.
Data source location	Canadian Prairies (Alberta, Saskatchewan, Manitoba), approximately 49°–55° N latitude and 96°–114° W longitude
Data accessibility	Publicly available via Mendeley Data with interactive visualization through a Google Earth Engine web app
Data Access

Repository name
A field boundary dataset for the Canadian Prairies derived from Sentinel-2 imagery using the Segment Anything Model (version 2)

DOI
10.17632/2y568rt76w.1

Direct Links

Download dataset: https://data.mendeley.com/datasets/2y568rt76w/1

Online visualization: https://cropagronomyusask.users.earthengine.app/view/field-boundaries

1. Downloading the Dataset

The complete dataset can be downloaded from Mendeley Data.

Steps:

Open the download URL in a web browser.

Select individual files or download the full dataset as a ZIP archive.

Extract the files to a local directory.

The dataset is provided in standard and cloud-optimized geospatial formats (e.g., Shapefile, GeoParquet) and can be opened using:

GIS software: QGIS, ArcGIS Pro

Python: geopandas

R: sf

2. Visualizing the Data Online (No Download Required)

An interactive Google Earth Engine web application is available for rapid visualization and inspection of the field boundaries.

Viewer:
https://cropagronomyusask.users.earthengine.app/view/field-boundaries

Steps:

Open the viewer link in a modern web browser.

Zoom and pan across Alberta, Saskatchewan, and Manitoba.

Toggle layers and inspect individual field boundary polygons.

Note: The web application is intended for visualization and quality assessment only and does not replace the downloadable dataset for analysis.

3. Using the Data in GIS and Analysis Workflows

The field boundary polygons can be integrated into spatial workflows and overlaid with other datasets such as:

Crop type and land cover maps

Yield and productivity datasets

Soil property layers

Climate and weather data

The dataset is suitable for applications in:

Precision agriculture

Large-scale land-use and land-cover mapping

Crop monitoring and modelling

Spatial machine learning and data cube development

Citation

When using this dataset in scientific publications or derivative works, please cite:

Ha, T., Nketia, K. A., Fernando, H., van Steenbergen, S., Neudorf, S., & Shirtliffe, S. (2025). A field boundary dataset for the Canadian Prairies derived from Sentinel-2 imagery using the Segment Anything Model. Mendeley Data, V1. https://doi.org/10.17632/2y568rt76w.1

Related Research Article

Ha, Thuan; Nketia, Kwabena Abrefa; Fernando, Hansanee; van Steenbergen, Sarah; Neudorf, Shawn; Shirtliffe, Steve J.
Field boundary delineation with seasonal Sentinel-2 imagery using the Segment Anything Model (SAM).
Available at SSRN: https://ssrn.com/abstract=5500667
DOI: http://dx.doi.org/10.2139/ssrn.5500667

License and Use

Please refer to the license information provided on the Mendeley Data repository page. Users are encouraged to acknowledge the data source and associated publication when using the dataset in research or operational applications.
