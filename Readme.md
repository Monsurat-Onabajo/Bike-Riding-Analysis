# PROJECT: WRANGLING, ANALYSING, VISUALIZING AND COMMUNICATING INSIGHTS OF DATA GOTTEN FROM FORD GOBIKE SYSTEM DATA

# Report 

> The main objective of this project is to Wrangle, Analyze, Visualize and communicate insights of data gotten from ford gobike system data. This notebook looks into using python-based analytics and data wrangling in an attempt to get insights on the dataset curated for this project.

> # GATHERING DATA

> The dataset used for this project was gotten [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv). The dataset was loaded using the traditional Pandas Read_csv function.

> # ASSESSING DATA

> The datasets were assessed visually using googlesheets and programmatically using the pandas function and the following issues are found

> * QUALITY ISSUES
>  * Year is in float form instead of int format
>  * Start station id and End station should be in int format
>  * There are missing values
>  * There are absurd birth years, e.g 1878-1930. it is not possible for people that are over or almost 100years to still be riding bike
>  * Start time and end time should be in datetime format
>  * User type and member gender should be in categorical 

> # TIDINESS ISSUES
> * Split Start time column into date and time column



# KEY INSIGHTS FOR PRESENTATION

* Which gender commonly ride bike
* Is gender of users dependent on how long they can ride bike
* Is age of bikers dependent on how long they can ride 
* When are most trips taken in terms of time of day
* How often do suscribers ride bikes?
* Is gender of users dependent on Duration of time that users travelled? 

# SUMMARY OF FINDINGS

The dataset used for this project was gotten from Ford Gobike Sysytem Data. This dataset includes information about individual rides made in  bike sharing system covering the greater San Fransisco Bay Area.
After Excessive data assessment, cleaning and data visualization was done so as to get insights from the data. I found out that the Larger percent of bikers in san fransisco bay area are male and duration the bikers travel is not dependent on the users Gender this is surprising because i always thought that bike riding was a male sport which was confirmed in the first insight i got, so i thought duration travelled will be dependent on gender but it is not.
I also found out that majority of Bikers ride in the morning while a very small percent of riders ride in the night. bikers that ride in daytime travel for longer time while riders that ride in the night travel for shorter time. this shows that duration of seconds travelled is dependent on parts of the day. 
Subscribers majorly use the bike sharing system more than customers and also age of bikers have negative correlation with duration of distance travelled. The higher the age of a rider, the shorter the duration of distance travelled. Bikers Age is dependent of Duration of Distance travelled


```python

```
