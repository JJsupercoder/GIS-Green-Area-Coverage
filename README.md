# Temporal Analysis of NDVI Trends and Prediction of Green Area Coverage Using LSTMs

## Overview
This project focuses on analysing long-term vegetation changes using Normalized Difference Vegetation Index (NDVI) and predicting future green cover trends using deep learning models. The study combines geospatial analysis with machine learning to monitor environmental changes over time in an urban campus setting.

## Objective
To study temporal changes in vegetation health and coverage using satellite imagery and build a predictive model capable of forecasting future NDVI trends using Long Short-Term Memory (LSTM) networks.

## Key Concepts & Tools
- NDVI (Normalized Difference Vegetation Index)
- Geospatial processing using QGIS
- Data processing and visualization using Google Colab
- Deep learning with LSTM networks
- Satellite imagery (Landsat NIR & Red bands)

## Literature Survey
The project report also includes research on:
- NDVI forecasting using machine learning
- GIS and remote sensing techniques
- Satellite image processing (Landsat, Sentinel)
- LSTM and deep learning for time-series forecasting

## Methodology
- Acquired multi-year Landsat satellite imagery (1988–2024)
- Extracted Red and Near-Infrared (NIR) bands for NDVI computation
- Cropped and processed study area using QGIS
- Generated NDVI maps for each year
- Computed statistical metrics (mean, median, quartiles)
- Introduced Fixed Coordinate Limit (FCL) to measure consistent greenery
- Trained LSTM model to capture temporal dependencies in NDVI data
- Predicted future NDVI maps and vegetation trends

## Key Results
- Significant decline in green cover observed over time (39% → <1% based on FCL metric)
- LSTM model successfully captured temporal patterns in NDVI data
- Improved forecasting compared to traditional linear regression models
- Generated NDVI-based predictions for future years

## Tech Stack
- Python (NumPy, Pandas, TensorFlow/Keras)
- QGIS (Geospatial preprocessing)
- Google Colab
- Landsat Satellite Data (USGS Earth Explorer)
- Excel (Statistical analysis and visualization)

## Applications
- Urban green space monitoring
- Environmental change detection
- Climate impact analysis
- Sustainable campus planning

## Future Work
- Integration of climate variables (rainfall, temperature, etc.)
- Transformer-based forecasting models
- Higher-resolution satellite imagery
- Improved anomaly detection for satellite data
- Enhanced FCL metric for better green area estimation
