# Ford GoBike System Data Exploration and Visualization


## Dataset
The Ford Gobike System dataset provides detailed information regarding bike riders of a bike sharing system in San 
Franscisco Bay for the month of February, 2019. Basically, it has 17 feartures however only five features were 
explored in the analysis which include duration_sec, member_birthyear, user_type, member_gender, and start_time. 

However, data wranging was perfomed to extract member_age, start_hour and start_day from member_birthyear, and start_time 
columns respectively and also converted duration from seconds to minute which was used in the analysis. The data can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)



## Summary of Findings
In exploring the data, I found out that the average trip duration was between 
5 to 20 minutes. Also, most riders are within the ages of 25 and 40 years. I also 
found that there was a very weak relatioship between trip duration and member's age, 
lower trip duration tend to be associated with higher age. I also found out that the trend 
of trip duration during weekdays are quite different from those of weekends, hence, average
trip duration during weekdays is slightly lower than weekends.

Finally, Subscribers and the Male genders are more likely to complete their trips 
in shorter time than their respective counterparts. 



## Key Insights for Presentation
For the presentation, I will present the impact the following variables(members' age, user_type, start_time, and gender)
on the average trip duration. I will start by introducing the variable of focus which is the trip duration. I will then 
look at the distribution of users' age and the plot the transformed scatter plot. 

I will then explore the trend of trip duration across start_day and also trip trends on weekdays(Monday to Friday) and weekends
(Saturday and Sunday) using box plot. The order variables (user_type and Gender) are afterward introduced using pointplot. 