# Ford GoBike Dataset Explanation
## Can PERÇİN

## Dataset

In this project, data visualization which is the final chapter in Udacity Data Analysis Nanodegree course will be demonstrated by using different techniques such as Univariate, Bivariate, Multivariate.

Ford GoBike is a bike sharing system and "201902-fordgobike-tripdata" will be used as the master data table in this project. Wrangling and explorating this data is going to be shown systematically in this section. After completing the exploration part, a presentation will be shown by using the outputs of exploration part.

Data wrangling stages;

1. "start_time" and "End_time" have wrong data types.

2. "bike_id", "start_station_id" and "end_station_id" have wrong datatypes(float). These should be string.

3. "user_type", "gender" and "bike_share_for_all_trip" have wrong datatype(str). These should be categorical.

4. Age column should be created by considering birth dates.

5. There are some bike ride data that have higher than 70 years old and null values in member_age column. These should be dropped to prevent outliers in our visualizations. At the end we can convert "member_age" column's datatype into int64.

6. We should subdivide start_time into day,month and year columns.


## Summary of Findings

Key results of this project are as follows;

    We point out that bike riders are 34 years old in mean.

    Non-subscriber customers are travelling longer than subscribers in one trip.

    Males are more likely to bike than females.

    Women tend not to choose memberships compared to men.

    Market St at 10th St. is intensely used for starting bike rides.

    San Francisco Caltrain Station 2 (Townsend St at 4th St) is intensely used for ending bike rides.


## Key Insights for Presentation

Non-subscriber customers are travelling longer than subscribers in one trip.

Males are more likely to bike than females. Women tend not to choose memberships compared to men.

Mostly used stations