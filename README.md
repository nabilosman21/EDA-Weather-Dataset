# Weather Dataset Analysis

## Overview
Welcome to the Weather Dataset Analysis project! This repository contains an exploration of a weather dataset aimed at uncovering insights into various weather parameters such as wind speed, visibility, pressure, and humidity. By diving deep into the data, we aim to answer key questions that enhance our understanding of weather conditions and their implications.

## Project Goals
The primary objective of this analysis is to:
- Examine unique weather parameters and their distributions.
- Investigate specific weather conditions and their occurrences.
- Analyze statistical measures for different weather metrics.
- Filter and present data based on specific conditions.

## Questions Explored
In this analysis, we investigate the following questions:
1. Find all unique 'Wind Speed' values in the data.
2. Count occurrences of 'Weather' being exactly 'Clear'.
3. Count occurrences of 'Wind Speed' being exactly 4 km/h.
4. Identify all null values in the dataset.
5. Rename the 'Weather' column to 'Weather Condition'.
6. Calculate the mean 'Visibility'.
7. Calculate the standard deviation of 'Pressure'.
8. Calculate the variance of 'Relative Humidity'.
9. Identify instances when 'Snow' was recorded.
10. Identify instances when 'Wind Speed' is above 24 and 'Visibility' is 25.
11. Compute the mean value of each column against each 'Weather Condition'.
12. Determine the minimum and maximum values of each column against each 'Weather Condition'.
13. Show all records where 'Weather Condition' is 'Fog'.
14. Identify instances when 'Weather' is 'Clear' or 'Visibility' is above 40.
15. Identify instances based on specific conditions combining 'Weather' and 'Visibility'.

## Tools and Libraries
- **Python**: The primary programming language used for analysis.
- **Pandas**: A powerful data manipulation library used for handling the dataset.
- **NumPy**: Used for numerical operations.
  
## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/weather-dataset-analysis.git

2. ```bash
   cd weather-dataset-analysis

3. Ensure you have the neccesarry libaries installed. You can install them using:
   ```bash
   pip install pandas numpy

4. Load the dataset and run the analysis:
   ```python
   import pandas as pd
   data = pd.read_csv("weather.csv")
   
## Key Findings 
Throughout this analysis, we uncovered several interesting insights, including:

- The range and distribution of wind speeds across different weather conditions.
- Statistical insights such as mean visibility and standard deviation of pressure.
- Instances of specific weather conditions, such as snow and fog.
   
