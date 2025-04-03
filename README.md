# Rise in Sea Level Analysis

This project is part of the **Data Analysis with Python** certification from [freeCodeCamp](https://www.freecodecamp.org/). The project involves analyzing global average sea level changes from 1880 to 2050 based on data provided in the `epa-sea-level.csv` file. Using this data, the project predicts future sea level changes and visualizes them using a scatter plot and linear regression models. The goal of this analysis is to understand how sea levels have risen over time and to predict their rise through the year 2050 based on two different models.

## Dataset

The dataset (`epa-sea-level.csv`) contains the following columns:
- **Year**: The year of the data point.
- **CSIRO Adjusted Sea Level**: The adjusted sea level (in inches) for the given year.
- **Lower Error Bound**: The lower bound of the error range for the sea level measurement.
- **Upper Error Bound**: The upper bound of the error range for the sea level measurement.
- **NOAA Adjusted Sea Level**: The sea level adjustment based on NOAA data.

### Data Source
The data is sourced from:
- Global Average Absolute Sea Level Change, 1880-2014 from the US Environmental Protection Agency (EPA) using data from CSIRO, 2015; NOAA, 2015.

## Objective

The goal is to:
1. Visualize the historical sea level data.
2. Use linear regression to predict the sea level rise by the year 2050.
3. Compare predictions using all data versus only data from the year 2000 onwards.

## Requirements

To run this project, you'll need the following Python libraries:
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **scipy**: For statistical functions like linear regression.

You can install these libraries using pip if you don't have them already:

```bash
pip install pandas matplotlib scipy

## Results
- The first line of best fit (orange) represents the sea level trend from 1880 to 2050.
- The second line of best fit (red) represents the trend from 2000 to 2050 predicting sea level rise if the current rate of change continues.

## Conclusion

An increase in sea level with a steeper slope is observed when we focus on the data after the year 2000. This trend is highly alarming and highlights the urgency of addressing climate change. The data points strongly suggest the need for policymakers to take immediate action in mitigating the effects of rising sea levels. Protecting island communities and preserving biodiversity should be prioritized to safeguard vulnerable regions from the escalating threat posed by climate change.

