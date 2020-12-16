# Causal Analysis of COVID-19 Data

## Group6 members:

* Thant Saing (42902347)
* Syed Hasan (45220700)
* Duy Hung Nguyen (46137920)
* Mekal Botani (46417397)

## Project Summary:
The Coronavirus disease, also known as COVID-19, is an infectious disease which studies have showen that it was caused by a newly found string of coronavirus.
The purpose of our project is to conduct a further analysis on the causal of the COVID-19. By exploring and analysing recent data obtained, we were able to visualise the factors that have assisted the spread of the virus. Factors such as the stringency levels of each country (different levels of lockdown regulations), as well as the frequency of international air travel.


## Datasets Summary:
The datasets we obtained at the beginning, were all in the .CSV format and were derived from three different legitimate sources; Our World in Data COVID-19 dataset, International Airlines - Airline by country of port data and United States Department of Transportation. However, after a thorough study of each dataset, we realised that the dataset from the United States Department of Transportation was not suitable enough to explore further. Hence, we decided not to include in our analysis.


### Dataset 1: 
[Our World in Data COVID-19 dataset](https://ourworldindata.org/coronavirus-source-data)

### Dataset 2:  
[International Airlines - Airline by country of port data](https://data.gov.au/dataset/ds-dga-ad89b4ff-541a-4729-b93c-4d2f5682e4c8/details)

### Dataset 3: (Not included)
[United States Department of Transportation](https://www.transtats.bts.gov/DatabaseInfo.asp?DB_ID=111)



## Variables Used (Dataset 1):

| Column Name        | Description   |
| -------------------|:-------------|
|new_deaths | The new number of deaths attributed to COVID-19|
| total_deaths_per_million | The total number of deaths attributed to COVID-19 per 1 million people |
| total_deaths	  | The total number of deaths attributed to COVID-19 |
| new_deaths_smoothed | The new number of deaths attributed to COVID-19 (7-day smoothed)  |
| new_cases | The new number of confirmed cases of COVID-19 |
| total_cases_per_million | The total confirmed cases of COVID-19 per 1 million people |
| total_cases |  The total number of confirmed cases of COVID-19 |
| new_cases_smoothed | The new number of confirmed cases of COVID-19 (7-day smoothed)    |
| stringency_index   | Safety measures that were taken in response to Covid-19 including school closures, workplace closures, and travel bans, rescaled to a value from 0 to 100 (100 = strictest response), and converted to levels from 1 to 5 (5 = strictest response)	   |
| location	  | Geographical location |
| aged_70_older  | The share number of the population that is 70 years and older in 2015 |
| date | The date of the population|


## Variables Used (Dataset 2):
| Column Name        | Description   |
| -------------------|:-------------|
| Passengers_In | Passengers inbound to Australia |
| Passengers_Out | Passengers outbound from Australia |
| Year | The year of travel |
| Month_num | The months of travel numbered (January = 1) |
| Airline | The names of Airlines in which passenger are traveling by |
