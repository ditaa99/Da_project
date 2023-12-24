# Traffic Accident Analysis in Zurich

## Overview
This project aims to analyze and visualize patterns in traffic accidents in Zurich since 2011, using data from the Swiss Open Data Portal. The analysis covers various aspects, including the frequency of different accident types, the distribution of accidents over days of the week and hours, trends over the years, and correlations between different variables.

## Author
**Dita Pelaj**

## Project ReadMe

### Data Source
- Swiss Open Data Portal

### Objective
- Analyze and visualize patterns in traffic accidents in Zurich since 2011

### Project Structure
- `RoadTrafficAccidentLocations.csv`: Data file

### Dependencies
- Matplotlib
- Pandas
- Seaborn

## Steps

### Data Processing
1. Check uniqueness and change data types for faster processing.
2. Check for null values in the dataset.

### Visualizations
We have generated a comprehensive set of visualizations to delve into various aspects of traffic accidents in Zurich. Starting with the **Accident Types Bar Plot**, we explore the frequency and distribution of different accident types, each highlighted with labeled bars. Moving on to the **Accidents by Day of the Week**, we analyze the frequency of incidents occurring on each day. The **Peak Hour of Accidents** visualization identifies the specific hours during which accidents peak for each day of the week. The **Accidents Over Time** plot reveals trends in the overall number of accidents throughout the years, emphasizing the peak year with a distinctive red star marker. To scrutinize the notable increase observed from 2014 to 2016, the **Accidents Over Time (2013-2017)** plot focuses on this specific period. Further insights into the monthly distribution of accidents in 2018 are provided by the **Monthly Distribution of Accidents in 2018** visualization. For a deeper understanding of relationships between numeric variables, the **Correlation Matrix** offers valuable insights. The **Accident Types Over Time** plot analyzes how different accident types evolve over the years. Delving into severity, the **Accident Types by Severity** visualization presents a stacked bar chart depicting the distribution of accident types by severity. Lastly, the **Severity of Accidents on Each Day of the Week** visualizes the severity of accidents through stacked bars for each day. The **Accident Types Heatmap** provides a heatmap illustrating correlations between accident types and days of the week, rounding out our comprehensive analysis.

### Instructions for Use
- Ensure the necessary dependencies are installed.
- Run the provided Python script on the dataset file.

### Results
- Comprehensive visualizations provide insights into traffic accident patterns in Zurich.
- Further analysis can be performed based on the generated visualizations.
