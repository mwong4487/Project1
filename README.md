# Project1
CSIT-165 Project 1

Project team members:
Marthew Wong
Lizbeth Ortega

#Objective 1

```{r ob1}
# Location of Max confirmations of COVID-19 is Hubei, China as of 01/22/2026
# Location of Max deaths of COVID-19 is Hubei, China as of 01/22/2026
# Hubei, China is equivalent to 73, since its the 73rd row. 
# Confirmations equal 444, deaths equal 17
library(readr)
time_series_covid19_confirmed_global <- read_csv("~/Downloads/time_series_covid19_confirmed_global.csv")
View(time_series_covid19_confirmed_global)
first_day_data <-as.Date("2020-01-22")
max_cases_location <- first_day_data[which.max(2020-01-22)]
location_name <- 73
if (73 > 0) {print(paste("The origin is predicted to be:", location_name,"based on max cases of", 444 ,"on date", 2020-01-22))} else {print("Origin cannot be determined from the first day data.")}
```

#Objective 2

```{r ob2}
#Where is the most recent area to have a first confirmed case?

```
