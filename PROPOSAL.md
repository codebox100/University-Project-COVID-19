# Causal Analysis of COVID-19 Data

## Project Summary

Coronavirus disease, known as COVID-19 is an infectious disease which is caused by a newly found string of coronavirus. It spreads primarily through discharge from the nose or droplets of saliva when an infected individual sneezes or coughs.

The majority of people who are tested positive with the disease will likely to experience mild to moderate respiratory illness and be able to recover without special treatment or care. International travel can have a direct impact on how quickly the virus spreads. Age and health are also significant factors, but these relate more to the number of deaths. In this analysis, we aim to look at both.

## Project Goal

The main goal of our project is to visualise the spread of COVID-19 virus by exploring recent data. We will also be predicting which factors have the biggest impact on the rate of infection by analysing data from both Australia and the United States of America. In order to achieve this, our focus is to address the following issues:
Does partial and complete lockdowns have any effect in the number of cases?
How does the frequency of international air travel affect the spread of the virus?


## Dataset Summary 

The datasets obtained are all in the .CSV format and were derived from three different legitimate sources; Our World in Data COVID-19 dataset, International Airlines - Airline by country of port data and United States Department of Transportation. Also, the column names are going to be modified to match the other datasets when combining them for the analysis. Moreover, depending on the datasets obtained, and what is suitable, we will either replace the null values with zeros or mean values for the purpose of cleaning the data.


## Data Analysis Techniques 

The techniques we want to adopt for our analysis includes linear and logistic regression, k-nearest neighbor and scikit-learn. Plots and heat maps are essential and will be generated throughout the analysis to compare the effect of stringencies between countries, predicting the trend of cases based on a single or multiple surrounding factors, and to visualise and achieve a better overall representation of our work.

## Project Plan

Milestone #1: Preparation of the Datasets
Obtain suitable datasets from legitimate sources, such as; WHO, International Airlines and United States Department of Transportation.
Clean the datasets, by:
Removing the null values 
Removing the outliers
Replacing the missing values
Matching column names to facilitate combining of tables
Combining the datasets for analysis

Milestone #2: Exploring datasets using functions and graphs
Using Scikit-Learn to perform concatenation, clustering, classification and regression techniques to find out the nature of correlations (positive or negative) and make future predictions.
  

## Relevant Prior Work

There was no relevant prior work found when the datasets were obtained from the three sources.


## Datasets/References: 

Dataset 1: Our World in Data COVID-19 dataset
Source: https://ourworldindata.org/coronavirus-source-data 

Dataset 2: International Airlines - Airline by country of port data
Source:https://data.gov.au/dataset/ds-dga-ad89b4ff-541a-4729-b93c-4d2f5682e4c8/details 

Dataset 3: United States Department of Transportation
Source: https://www.transtats.bts.gov/DatabaseInfo.asp?DB_ID=111
