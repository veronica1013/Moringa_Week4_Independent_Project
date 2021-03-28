# Moringa_Week4_Independent_Project

## DATA REPORT FOR SHARED ELECTRIC CAR SERVICE
### Introduction
Dalberg data insights obtained real time data from opendataparis.com. The main aim was to identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018. 

The final deliverable will comprise of:
Business Understanding
Data understanding
Data Preparation
Analysis
Recommendation
Evaluation

### Business Understanding
Business Overview
According to wikipedia Autolib' was an electric car sharing service which was inaugurated in Paris, France, in December 2011. It closed on 31 July 2018. It was operated by the Bollore' industrial group, and complemented the city's bike sharing system,Velib', which was set up in 2007. The Autolib' service maintained a fleet of all-electric Ballore' Bluecars for public use on a paid subscription basis, employing a citywide network of parking and charging stations. As of 3 July 3, 2016, 3,980 Bluecars had been registered for the service and had more than 126,900 registered subscribers; Autolib' furthermore offered 1,084 electric car stations in Paris agglomeration with 5,935 charging points. Since beginning operations in Paris, Autolib' expanded its business to the cities of Lyon and Bordeaux. Bolloré also signed deals to begin operating offshoots of Autolib' in London and Indianapolis in 2015, Turin in 2016 and Singapore in 2017.


#### Business Objective
The main aim was to identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018. 

#### Business Success Criteria
For the business to be successful, asking some questions will help in achieving the business objective. Some of the questions that this process seek to answer are:
Which ones were the most used city for the three days?
Which cities were the most used during business and home hours?
Most used city for the three days?

#### Assessing the Situation
1. Resource Inventory
DataSets
The autolib csv dataset was obtained from this link [http://bit.ly/autolib_dataset] 
The details to the description of the csv autolib dataset was obtained from this link [here].
Software (Github, VsCode, Python, Jupyter, Numpy, Pandas and Jira)


2. Assumptions
The main assumption was that the data provided is correct but might:
 have included timeframe outside the project scope (April 1, 2018 to April 9, 2018)
Have missing data within the required timeframe
This assumption was based on the fact that the data when Dalberg Data Insights were obtaining the data, they had collected data at the following times:
First pilot: every 5 minutes from October 6, 2017, 11:13 AM  to October 8, 2017, 10:21 AM 
Second Pilot: every minute from October 9, 2017, 15:53 PM to October 10, 2017, 15:31PM 
Production: every minute from October 30, 16:59 PM to July 31, 2018, 23:59 PM  (date of the end of the Autolib services, although our automatic downloads went on after that).
 
They further noted that during the collection periods, on some occasions, the download failed, which created dome gaps in the data. These gaps are represented on Figures 1 and 2 on this autolib data description document . Except for an important gap from November 11 to November 14, 2017, missing files were rare


3. Constraints
There were no constraints as the data was readily available 

#### Data Mining Goals
Our data mining goals for the project are:
Identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.
What is the most popular hour for returning cars?
What station is the most popular?
Overall?
At the most popular picking hour?
What postal code is the most popular for picking up Blue cars? Does the most popular station belong to that postal code?
Overall?
At the most popular picking hour?
Do the results change if you consider Utilib and Utilib 1.4 instead of Blue cars? 

#### Data Mining Success Criteria
Our success will be measured by the following criteria:
Finding the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018

## Data Understanding
Data Understanding Overview
 

Verifying Data Quality
There were missing values in the availed datasets.

## Data Preparation
Below are the steps followed in preparing the data for analysis:
Importing the libraries
This entailed importing the libraries that will be used on the jupyter notebook. These libraries were pandas and numpy (import pandas as pd, import numpy as np)

Loading Data
  
Dimensions of the Dataframes

Merging the Datasets

Missing data
The next thing I did was to check the total rows with missing data in the concatenated datasets and then I dropped the rows that had the missing data.

Deriving New Attributes


## Analysis and Findings
 

## Recommendation
The outcome of the analysis was that the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018 was the 14th hour. This is because at that hour, there were no bluecars at the station. Meaning all the cars had been picked for use.

I would recommend that the company should consider adding more cars during this hour to cater for the business need.

 
The link to the jira account that documents my project plan is found here (link)

