# Pune Housing Data Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%230C55A5.svg?style=for-the-badge&logo=seaborn&logoColor=white)

## Overview

This project analyzes housing data from Pune, India, focusing on:
- Data exploration and cleaning
- Feature engineering
- Visualization of housing trends

## Dataset

The dataset contains 13,320 records with 9 features:
- `area_type`: Type of housing area
- `availability`: When the house is available
- `size`: Size in BHK/Bedroom
- `society`: Housing society name
- `total_sqft`: Total square footage
- `bath`: Number of bathrooms
- `balcony`: Number of balconies
- `price`: Price in lakhs
- `site_location`: Location of property

## Key Features

### Data Cleaning
- Simplified "availability" to binary "Ready to Move"/"Not Ready to Move"
- Extracted numerical values from "size" column
- Converted "total_sqft" ranges to median values

### Exploratory Analysis
- Examined distributions of key features
- Visualized categorical variables
- Analyzed missing values

### Visualizations
- Count plots for categorical features
- Distribution analysis

## Requirements

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage

1. Clone the repository
2. Install requirements with `pip install -r requirements.txt`
3. Open and run the Jupyter notebook

