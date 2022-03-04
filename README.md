# BloomTech Unit 2 Build Week Predictive Modeling Project
#### Contents include my advanced assignment for BloomTech's Unit 2 Build Week
---
## Predicting Forest Fires
This project uses publicly available data, found [here](https://archive.ics.uci.edu/ml/datasets/forest+fires), from a paper by Cortez and Morais [2007].

#### **Attribute Information:**
This dataset consists of two geographical features, two temporal features, four [Fire Weather Index (FWI)](https://www.nwcg.gov/publications/pms437/cffdrs/fire-weather-index-system) features, four meteorological data features, and our target: area. 
- X: x-axis value corresponding to location of fire on map of Montesinho park [Cortez and Morais, 2007] 
- Y: y-axis value corresponding to location of fire on map of Montesinho park [Cortez and Morais, 2007] 
- month: month of the year- "jan" to "dec"
- day: day of the week- "mon" to "sun"
- FFMC: Fine Fuel Moisture Code from FWI system
- DMC: Duff Moisture Code from FWI system
- DC: Drought Code from FWI system
- ISI: Initial Spread Index from FWI system
- temp: temperature (&deg;C)
- RH: relative humidity (%)
- wind: wind speed (km/h)
- rain: accumulated precipitation from previous 30 minutes (mm/m<sup>2</sup>)
- area: total area burned (ha)

Note: The majority of the dataset was already clean and did not require further transformation. However, the area feature was an exception; 47.8% of the recorded fires were values of 0.0 hectares, which produced a right skewed target variable. These zero values actually represent areas of less than 0.01 ha, or 100 m<sup>2</sup>.

#### **Citation:**

[Cortez and Morais, 2007] P. Cortez and A. Morais. A Data Mining Approach to Predict Forest Fires using Meteorological Data. In J. Neves, M. F. Santos and J. Machado Eds., New Trends in Artificial Intelligence, Proceedings of the 13th EPIA 2007 - Portuguese Conference on Artificial Intelligence, December, Guimarães, Portugal, pp. 512-523, 2007. APPIA, ISBN-13 978-989-95618-0-9. Available at: [Web Link](http://www3.dsi.uminho.pt/pcortez/fires.pdf)
