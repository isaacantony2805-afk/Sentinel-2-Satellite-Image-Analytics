# Sentinel-2 Satellite Image Analytics

Real Sentinel-2 satellite image analysis using spectral indices, computer vision, and machine learning.

## Project Overview

This project analyzes real Sentinel-2 multispectral satellite imagery to extract useful information about land cover and surface features.

The workflow combines remote sensing techniques, classical computer vision, convolution-based feature extraction, and machine learning.

## Objectives

- Analyze multispectral Sentinel-2 satellite data
- Calculate spectral indices such as NDVI, NDWI, EVI, and NDTI
- Perform land-cover analysis
- Apply computer vision techniques to satellite imagery
- Demonstrate convolution and feature extraction
- Apply K-Means clustering
- Apply Random Forest classification
- Visualize the analysis through dashboards

## Workflow

1. Sentinel-2 data preparation
2. Spectral index calculation
3. Land-cover analysis
4. Computer vision feature extraction
5. K-Means clustering
6. Random Forest classification
7. Dashboard-based visualization

## Computer Vision Techniques

- Grayscale conversion
- Sobel edge detection
- Canny edge detection
- FFT and frequency-domain analysis
- Frangi filtering
- 2D convolution
- ReLU activation
- Max pooling

## Machine Learning

### K-Means
Unsupervised clustering used to group pixels based on their spectral characteristics.

### Random Forest
Supervised classification used for land-cover classification using extracted spectral features.

> Note: The classification labels used in this project were generated using spectral threshold rules from the same Sentinel-2 scene. Therefore, the reported accuracy should not be interpreted as independent ground-truth validation.

## Dashboards

The project contains three dashboards:

- Main Satellite Analysis
- Computer Vision Feature Extraction
- Machine Learning Results

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook
- Sentinel-2 satellite data

## Repository Structure

```text
Sentinel-2-Satellite-Image-Analytics/
├── README.md
├── sentinel_2_satellite_image_analytics.ipynb
└── dashboards/
    ├── Dashboard_1_Analytics_Final_HD.png
    ├── Dashboard_2_CV_Features_Final_HD.png
    └── Dashboard_3_ML_Final_HD.png
