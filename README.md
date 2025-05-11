# Data Analysis project
### This projected involves analysis of covid19 data to gain various insights
# COVID-19 Data Analysis

## Overview

This project analyzes COVID-19 data to extract meaningful insights and visualize trends. The analysis includes data on confirmed cases, deaths, vaccination rates, and other metrics. The project uses Python and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Requirements

To run this project, you need the following:

- Python 3.7 or higher
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

Install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn
pip install pandas numpy matplotlib pandas
pip install pandas numpy matplotlib matplotlib
pip install pandas numpy matplotlib numpy
```
## Dataset Details

### 1. `country_wise_latest.csv`
This dataset contains the latest COVID-19 statistics for each country. Key columns include:
- **Country/Region**: Name of the country or region.
- **WHO Region**: The World Health Organization region the country belongs to.
- **Confirmed**: Total confirmed COVID-19 cases.
- **Deaths**: Total deaths due to COVID-19.
- **Recovered**: Total recovered cases.
- **1 week change**: Change in confirmed cases over the last week.
- **1 week % increase**: Percentage increase in confirmed cases over the last week.

### 2. `country_vaccinations.csv`
This dataset contains vaccination data for each country. Key columns include:
- **country**: Name of the country.
- **date**: Date of the recorded data.
- **daily_vaccinations_per_million**: Daily vaccinations per million people.
- **total_vaccinations**: Total vaccinations administered.
- **people_vaccinated**: Total number of people vaccinated.
- **people_fully_vaccinated**: Total number of people fully vaccinated.

## Additional Insights

### 1. Death Rate Calculation
The death rate is calculated as:
```python
total_death_case = covid_data['Deaths'].sum()
total_confirmed_case = covid_data['Confirmed'].sum()
death_rate = total_death_case / total_confirmed_case
print(f"Death Rate: {death_rate:.2%}")
```
---

## How to Run

1. Clone the repository or download the notebook file.
2. Place the datasets (`country_wise_latest.csv` and `country_vaccinations.csv`) in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or any compatible IDE.
4. Run the cells sequentially to execute the analysis.

---

