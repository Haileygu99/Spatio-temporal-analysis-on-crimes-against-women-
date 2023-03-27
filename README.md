# Spatio-temporal-analysis-on-crimes-against-women-
Spatio-temporal analysis of crimes against women in Uttar Pradesh (India)

This project focuses on two crimes against women in Uttar Pradesh, which is the most populated state in India and has the highest percentage of overall crimes against women, based on 2017 report by the National Crime Records Bureau. 

The two crimes are 

1. Rapes' incidence 
2. Dowry deaths


Rape in India is a serious problem and it is believed to be under reported, while dowry death is a form of crime that is related to the dowry system, a cultural practice that perpetuates the oppression, torture, and murder of women. 

Aim of the project:
- Perform a spatio-temporal analysis of rapes' incidence and dowry deaths in the 70 districts of Uttar Pradesh during the period 2001 - 2014. 
(The data have been obtained from the National Crime Record Bureau.)


The data and SpatialPolygonDataFrame objects available for this project are collected in a .RData file called “CrimeUttarPradesh.RData”.

The data include the following variables:
- dist: Districts
- state: Satte (Uttar Pradesh)
- year: Year (2001:2014)
- rape: Observed number of rapes
- dowry: Observed number of dowry deaths
- pop: Female population between 15 and 49 years (obtained by linear interpolation)
- e_rape: Expected number of rapes
- e_dowry: Expected number of dowry deaths
- smr_rape: Standardized incidence ratio (SMR) of rapes
- smr_dowry: Standardized mortality ratio (SMR) of dowry deaths
- ID_area: Area Identifiers (Districts)
- ID_year: Time Identifiers (Year)
- ID_area_year: Area-time Identifiers (Districts-Year)

Moreover, the SpatialPolygonDataFrame objects are:
- carto_india: SpatialPolygonDataFrame object with the cartography of the 33 states (without islands) of India
- carto_up: SpatialPolygonDataFrame object with the cartography of the 70 districts (year 2001) of Uttar Pradesh


SUGGESTIONS: 
- We suggest to perform an analysis for each crime separately. 
- Also, we suggest of attempting an interation space-time of type.
