# City_bike_NY
The full data for City bike of New York data can be found [here](https://www.citibikenyc.com/system-data) while the subset of dataset I used is reported in [Resources20-21](./Resources20-21).\
The visualization was performed using [Tableau Public](https://public.tableau.com/en-us/s/) and the story can be found [https://public.tableau.com/profile/giada.innocenti#!/vizhome/City_Bike_NY_STORY/Story1?publish=yes].\
In the jupyter notebook reported in this repository all the csv for the period of time that start in May 2020 and ends in Apr 2021 are read and merged in a fact table using pandas. The dataset was pretty clean on its own but since Tableau Public has a limit of 15M rows a minimal data cleaning was done:
1. all the people that were born before 1940 were dropped since they are more tha 80 years old.
2. all the people that identified as unknown gender were dropped.
\
Finding trends in this case was not very easy since NY was in a severe lockdown for most of the last year and as a consequence I believe the use of the bike share was somehow impacted with respect to previous years.\
The main trends observed are:
* female users are using the bike for the longest time on average, specifically female individuals that were born between 1995 and 2004 are traveling the longest.
* Some stations do NOT have any female user as end destination.
* It seems that the close to the city center the bikes are picked up the longest are kept, probably to run multiple errands.
