# Hydropower Generation Dataset (Bangladesh)

This repository contains a processed dataset of hydropower generation from the Karnaphuli Power Station, combined with satellite-based weather data from NASA IMERG.

## Dataset Information
- Samples: 1759  
- Features: 11  
- Time span: January 2021 – November 2025  
- Format: CSV (time-series)  

## Features
- Day Peak Power (MW)  
- Evening Peak Power (MW)  
- Temperature (°C)  
- Relative Humidity (%)  
- Precipitation (mm)  
- Solar Radiation (W/m²)  
- Wind Speed (m/s)  
- Surface Pressure  
- Latent Heat Flux (LHF)  

## Links
- Paper: https://doi.org/10.1109/IATMSI68868.2026.11466157  
- Zenodo Dataset: https://doi.org/10.5281/zenodo.19989909 
- Kaggle Dataset: https://doi.org/10.34740/kaggle/dsv/16061517


## Applications
- Energy forecasting  
- Machine learning regression  
- Climate impact analysis  

## Example Usage

```python
import pandas as pd

df = pd.read_csv("dataset/karnaphuli_hydropower_dataset.csv")
print(df.head())
