# Master_Thesis

## 📂 Thesis Codes Overview: LST Analysis & Forecasting

This repository contains Python scripts for analyzing and forecasting **Land Surface Temperature (LST)** in **Shanghai** using geospatial data and deep learning techniques. The project is part of a master's thesis focused on understanding the spatial dynamics of the Urban Heat Island (UHI) effect and its relation to industrialization.

### 🛰️ `lst_assignment.ipynb`
This script processes MODIS satellite-derived LST data and extracts spatial features across Shanghai. Key functions include:
- Clipping raster images to administrative boundaries
- Computing monthly average LST (2000–2024)
- Integrating spatial features from industrial zones, green areas, water bodies, and infrastructure
- Generating pixel-level feature datasets for machine learning modeling

### 🔮 `lstm_assignment.ipynb`
This script implements an LSTM (Long Short-Term Memory) model to forecast LST trends:
- Prepares standardized LST time series data
- Creates input sequences for LSTM training
- Trains and evaluates the model on historical monthly data
- Forecasts future LST values for 2025–2030
- Visualizes results with past observations, test set performance, and future projections

> 📈 These codes combine remote sensing, geospatial analysis, and deep learning to uncover and predict urban heat patterns in Shanghai.

### Requirements
- Python 3.8+
- `numpy`, `pandas`, `rasterio`, `geopandas`, `matplotlib`, `torch`, `scikit-learn`
