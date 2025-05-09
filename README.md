## COVID-19 Data Visualization and Analysis

This project provides an interactive and exploratory analysis of the global COVID-19 pandemic using the [OWID COVID-19 dataset](https://github.com/owid/covid-19-data). It includes data cleaning, exploratory data analysis, and the creation of interactive choropleth maps to visualize cases, deaths, and vaccination coverage across countries.

### Project Structure

- [`owid-covid-data.csv`](owid-covid-data.csv): Main dataset from Our World in Data.
- [`owid-covid.ipynb`](owid-covid.ipynb): Jupyter notebook for data loading, cleaning, and exploratory analysis (trends, comparisons, and insights).
- [`choropleth-maps.ipynb`](choropleth-maps.ipynb): Jupyter notebook for creating interactive choropleth maps (cases, deaths, vaccination, and animated time series).

### Features

- Data cleaning and handling of missing values.
- Time series analysis of COVID-19 cases, deaths, and vaccinations for selected countries.
- Calculation and visualization of death rates and vaccination percentages.
- Interactive choropleth maps using Plotly for:
  - Total cases by country
  - Death rates by country
  - Vaccination coverage by country
  - Animated monthly progression of cases

### Key Insights summary

- **Vaccine Rollout:** Among the selected countries, the United States and Germany demonstrated the fastest initial vaccine rollout, with a rapid increase in both total and fully vaccinated individuals. Kenya and India showed a slower but steady increase in vaccination rates.
- **Trends in Cases and Deaths:** The United States, India, and Brazil experienced the highest total number of COVID-19 cases and deaths over the observed period. Notably, India had significant spikes in new cases during mid-2021, corresponding to the Delta variant wave.
- **Death Rate Differences:** European countries like Germany, France, Italy, and Spain generally exhibited lower death rates relative to total cases compared to Brazil and the United States, possibly reflecting differences in healthcare capacity and public health interventions.
- **Population Impact:** Despite having a large population, China reported relatively low case and death numbers, which may be attributed to strict containment measures and reporting practices.
- **Vaccination Coverage:** By the latest available data, most European countries and the United States achieved higher percentages of fully vaccinated populations compared to Kenya and India.


### Highlight Anomalies and Patterns

- **Reporting Anomalies:** Some countries, such as China and Russia, display unusually flat or abrupt changes in case and death counts, suggesting possible underreporting or data lags.
- **Outlier Events:** India experienced a dramatic spike in new cases and deaths during the Delta wave, standing out as a significant outlier compared to other countries during that period.
- **Vaccination Uptake Patterns:** Kenya's vaccination curve remained much flatter than other countries, highlighting disparities in vaccine access and distribution.
- **Death Rate Fluctuations:** Early in the pandemic, several countries showed high death rates due to limited testing and overwhelmed healthcare systems, which gradually decreased as testing and treatment improved.
- **Plateau Effects:** In some countries, the number of new cases and deaths plateaued after major vaccination milestones, indicating a potential correlation between vaccination coverage and pandemic control.
