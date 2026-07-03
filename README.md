# Water Hyacinth Spread Detection and Analysis using Random Forest

## Overview

This project focuses on the **detection, mapping, and seasonal analysis of Water Hyacinth (*Eichhornia crassipes*)** in **Vembanad Lake, Kerala**, using **Google Earth Engine (GEE)** and the **Random Forest** machine learning algorithm. By leveraging multi-temporal Sentinel-2 satellite imagery, the study monitors the spatial distribution and seasonal dynamics of this invasive aquatic species while estimating its areal extent.

The workflow integrates cloud-based geospatial processing, spectral feature extraction, machine learning classification, and quantitative analysis to provide an efficient and scalable approach for monitoring invasive vegetation.

---

## Objectives

- Detect and map Water Hyacinth using Sentinel-2 imagery.
- Monitor seasonal variations in the spread of the invasive species.
- Apply the Random Forest classifier for accurate land cover classification.
- Estimate the spatial extent of infestation across different seasons.
- Support ecosystem management through remote sensing and machine learning.

---

## Study Area

**Vembanad Lake**, Kerala, India

- Largest lake in Kerala
- Longest lake in India
- Ecologically significant Ramsar wetland
- Severely affected by invasive Water Hyacinth infestation

---

## Methodology

The project followed the workflow below:

1. Acquisition of Sentinel-2 satellite imagery.
2. Cloud masking and median composite generation.
3. Feature extraction using spectral indices:
   - NDVI
   - NDWI
   - EVI
   - MNDWI
4. Training Random Forest classifier using labelled samples.
5. Seasonal classification for four seasons of 2023.
6. Accuracy assessment of classification results.
7. Area estimation and spatial analysis of Water Hyacinth spread.

---

## Datasets Used

- Sentinel-2 Multispectral Imagery
- Google Earth Engine Data Catalog
- Training and Validation Samples

---

## Tools & Technologies

- Google Earth Engine (GEE)
- JavaScript
- Random Forest Machine Learning
- Sentinel-2 Satellite Imagery
- Remote Sensing
- GIS & Spatial Analysis

---

## Key Features

- Cloud-based geospatial analysis
- Multi-temporal satellite image processing
- Machine learning-based classification
- Seasonal monitoring of invasive vegetation
- Area estimation of Water Hyacinth infestation
- Accuracy assessment using confusion matrices
- Spatial hotspot identification

---

## Results

The Random Forest model achieved an overall classification accuracy of approximately **92.5%**, demonstrating its effectiveness in detecting Water Hyacinth from Sentinel-2 imagery. The analysis revealed significant seasonal variation, with the highest infestation occurring during **April–June**, where the spread increased from approximately **10.2 km²** to **20.1 km²**. Seasonal distribution maps and quantitative area estimates provided valuable insights into infestation patterns, supporting effective monitoring and management of invasive aquatic vegetation.

---

## Skills Demonstrated

- Remote Sensing
- Google Earth Engine
- Machine Learning for Geospatial Applications
- Random Forest Classification
- Time-Series Analysis
- Spatial Analysis
- Satellite Image Processing
- Accuracy Assessment
- Environmental Monitoring
- GIS Mapping

---
## Applications

- Invasive Species Monitoring
- Wetland Ecosystem Management
- Environmental Monitoring
- Conservation Planning
- Remote Sensing Research
- Machine Learning in GIS

---

## Future Enhancements

- Integrate Sentinel-1 SAR data for improved detection under cloudy conditions.
- Explore deep learning models such as CNNs for enhanced classification accuracy.
- Develop an automated monitoring dashboard for real-time invasive species tracking.
- Extend the workflow to other freshwater ecosystems using multi-sensor satellite data.

<img width="379" height="495" alt="study" src="https://github.com/user-attachments/assets/5e257fa0-1d4d-448c-8ccc-71a06dc3d85e" />
<img width="556" height="388" alt="method" src="https://github.com/user-attachments/assets/1b9880bc-389f-46e6-9bea-b30e770a5a8e" />
<img width="728" height="774" alt="spread" src="https://github.com/user-attachments/assets/118f1756-1788-42fa-a0ab-d39de87d0a4e" />
<img width="612" height="676" alt="accuracy" src="https://github.com/user-attachments/assets/5f3b6290-9c35-4e61-ac25-9befa407a658" />
<img width="620" height="455" alt="spatial accuracy" src="https://github.com/user-attachments/assets/9294e98e-a6fc-4dab-bcf5-fe36f41d9c43" />
<img width="460" height="267" alt="cover" src="https://github.com/user-attachments/assets/e700becb-bcf2-4b56-9c3c-aa477ab88842" />

