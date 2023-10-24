## California's Covid-19 Data Analysis

As this is a healthcare issue, analysis of the Covid-19 data is crucial. Priorities should always be given to healthcare. This Corona Virus attack caused significant harm to the entire world, including the commercial, business, transportation, and many other sectors. Therefore, the analysis of Covid-19 data may aid in the discovery of solutions to lessen the likelihood that the number of Covid-19 cases will rise in the coming days.

### Dataset

In this project I am extracting Covid data for California from the New York Time (NYT) Covid data. I am doing analysis on this data to find some hidden patterns in the dataset by creating some visualizations of the data.

I have taken data from ![here]("https://raw.githubusercontent.com/nytimes/covid-19-data/master/rolling-averages/us-counties.csv"). The primary data set includes the daily cumulative number of cases and deaths reported in each county and state across the United States since the outbreak began. For more information about data is available [here](https://github.com/nytimes/covid-19-data).

This dataset contains 33040 obdervations and with 10 variables. The quantitative variables are date, cases, cases_avg, cases_avg_per_100k, deaths, deaths_avg and deaths_avg_per_100k. Qualitative variables are GEOID, county, and state. The variables details are as followes.

date - Date 
GEOID - Containg the different ID's for each counties
county - County Name
state - State to which the county belongs to.
cases - Number of cases recorded for the given date.
cases_avg - Avarage cases for the given data for a county.
cases_avg_per_100k - Average cases per 100k.
deaths - Total deaths recorded on the day in a county.
deaths_avg - Avarage deaths for the given data for a county.
deaths_avg_per_100k - Average Deaths per 100k.
