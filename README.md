# COVID-19 Data Analysis
This project analyzes COVID-19 data from various countries, exploring relationships between cases, deaths, recoveries, testing rates, and population.

## Dataset

The [dataset](https://github.com/Negar-Mazaheri/covid-19-analysis/blob/main/covid_19.csv) used in this analysis contains the following attributes:
- country: Indexed on country
- continent: The continent to which the country belongs
- population: Population of the country
- day: Last updated date
- time: Last updated time
- Cases: Total number of cases
- Deaths: Total number of deaths
- Recovered: Total number of recoveries
- Tests: Number of tests conducted

## Requirements

To run this analysis, you'll need Python 3.x and the following libraries:
- numpy
- pandas
- matplotlib
- seaborn


## Visualizations

The script generates several visualizations, including:
- Pair plot of key variables
- Deaths by continent
- Cases by continent
- Deaths by country
- Cases by country
- Correlation heatmap
- Tests by country
- Relationship between testing rate and case rate
- Population vs Cases scatter plot
- Active cases by country
