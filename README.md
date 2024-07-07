# Agriculture Data

This repository contains datasets generated for the purpose of training and testing machine learning models for predicting greenhouse gas emissions (CO2 and N2O) in agricultural fields. These datasets include various features related to agricultural practices and environmental conditions.

## Dataset Description

### Features

1. **Soil Moisture**: Measured in percentage, indicating the moisture content of the soil.
2. **Temperature**: Measured in degrees Celsius, indicating the temperature of the field.
3. **Crop Type**: The type of crop grown in the field. The possible values are Wheat, Corn, Rice, and Soybean. (One-hot encoded)
4. **Fertilizer Use**: Measured in kg/ha, indicating the amount of fertilizer used.
5. **Soil Type**: The type of soil in the field. The possible values are Loam, Clay, and Sand. (One-hot encoded)
6. **Rainfall**: Measured in mm, indicating the amount of rainfall received.
7. **pH Level**: Measured in pH units, indicating the acidity or alkalinity of the soil.
8. **CO2 Emissions**: Measured in kg/ha, indicating the carbon dioxide emissions from the field.
9. **N2O Emissions**: Measured in kg/ha, indicating the nitrous oxide emissions from the field.

### Files

1. **GreenHouse Emission dataset.csv**: A large dataset containing 10,000 samples.

## Usage

These datasets can be used to train and test machine learning models for predicting CO2 and N2O emissions based on various features. The datasets are generated with random values and are intended for demonstration and educational purposes.

### Example Usage

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('GreenHouse Emission dataset.csv')

# Display the first few rows
print(df.head())
