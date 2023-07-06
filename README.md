# How Does Income and Population Density Influence the Death and Case Rate of Covid-19 in Los Angeles?

### At A Glance
For our group project we decided to compare 3 publicly available data sets to try and gain an insight as to what may have contributed to covid cases in Los Angeles.

### Sources 
- [API](https://www.openstreetmap.org): OpenStreetMap was used to get the Lat and Lon coordinates for each neighborhood
- [Median Income Dataset](https://maps.latimes.com/neighborhoods/income/median/neighborhood/list/): Median Income data is from an article by the Los Angeles Times. The article ranks 265 neighborhoods in LA from the highest to lowest income
- [Population Density Dataset](https://maps.latimes.com/neighborhoods/population/density/neighborhood/list/): Population Density data is also from an article by the Los Angeles Times. The article ranks 265 neighborhoods in LA from  the highest to lowest population density in people per sq mile.
- [Vaccination Rates by Neighborhood Dataset](https://catalog.data.gov/dataset/vaccination-rates-by-neighborhood): Vaccination Rates data is from data.gov, specifically from the City of Los Angeles's page on the site. The dataset shows the covid cases, deaths, and vaccination rate of cities and communities in Los Angeles.

### Statistical Findings
Death Rate vs Income:
p-value: 6.649608696312204e-10
r-value: -0.4475943074526824

Death Rate vs Population Density
p-value: 0.0005441086427745205
r-value: 0.2602517883570094

Death Rate vs Percent Vaccinated
p-value: 0.011958207603335361
r-value: -0.19071376391546443
