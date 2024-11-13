# Climate-Change-Predictor
Created a climate change predictor model using linear regression

Here’s a concise yet informative README template for your climate change temperature prediction project:

---

# Climate Change Temperature Prediction Model

This project uses a Machine Learning model to predict global temperature trends based on historical climate data, demonstrating potential future temperature increases due to climate change. The model employs linear regression on historical average temperature data and visualizes the projected temperature changes through histograms.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Setup and Requirements](#setup-and-requirements)
- [Usage](#usage)
- [Results and Visualization](#results-and-visualization)
- [Future Work](#future-work)

## Overview
The purpose of this project is to analyze historical temperature data to predict future global temperature increases. This model provides:
- Predictions of temperature for any specified year.
- Comparisons with a manually set baseline year to illustrate the projected temperature increase over time.
- Visualization of temperature change distribution with histograms.

## Project Structure
- `climate_data.csv`: Dataset containing historical global temperatures by year.
- `temperature_prediction.py`: Python script with data processing, model training, prediction, and visualization functions.
- `README.md`: Project description and usage guide.

## Dataset
This project uses climate data from `climate_data.csv`. The dataset includes:
- Yearly average temperatures (°C).
- Historical data points are preprocessed for use in the regression model.

## Setup and Requirements
### Requirements:
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `sklearn`
  
Install requirements via:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage
1. **Load Data**: Update the `climate_data.csv` path if needed.
2. **Run Model**: Execute the Python script to make predictions.
   ```bash
   python temperature_prediction.py
   ```
3. **Predict Temperature**: Enter the desired year when prompted to get a predicted temperature and view a histogram of temperature changes.

## Results and Visualization
- The script outputs predicted global temperatures for a specified year, relative to the baseline year.
- A histogram displays the distribution of temperature changes relative to the baseline, with the predicted increase highlighted.

## Future Work
Enhancements could include:
- Integrating more sophisticated models like Polynomial Regression or Time Series Analysis.
- Exploring additional datasets to include region-specific data or more recent climate observations.

---

