# START-datset
## Introduction:
This was our fourth class project. The focus of this project was to use tableau to create visualizations and implement bayesian inference and regression. The Start Dataset can be found [here](https://www.start.umd.edu/gtd/).

## Data:
The dataset consists of over 170,000 observations. Each observation is a terrorist attack event that occured between the years 1970 and 2016.

## Objectives
The objectives of this project were to:
1. create visualizations representing attack types wordwide with a timelapse
2. use bayesian inference to compare to locations or time eras
3. use bayesian regression to predict missing data for the number of bombings that occured in the year 1993

## Findings:
I compared number of domestic terrorist events in the US during the Bush administration to the number of events that occured during the Obama administration, when there was a notable trend in white supremacist groups. The two eras were not significantly different using the prior of the average number of terrorist acts in the US from 1970 to 2016. I also used bayesian regression to impute the number of bombings based one the preceeding and following 5 years from 1993. I took the number of bombings per country per year and used Pymc3 to impute the value. My regression predicted that 1380 bombings occured that year.
