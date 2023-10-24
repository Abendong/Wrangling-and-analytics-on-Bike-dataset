# Explorative Analysis of FordGobike Dataset to Understand Consumer needs to Better serve them

By Akoanung Ayaba Abndong


## Dataset

> The dataset chosen for my project is the Fordgobike dataset. I choosed this dataset particular because it gives me the possibility to practice wrangling more before demonstrating insight from the data through visualizations. 
The original dataset has 174952 fordgobike rides with 16 columns of diffrent atributes. The original dataset has been modified nonetheless and now has 174952 forgobike rides with 22 columns with different attributes which includes; 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'member_age', 'start_station_id', 'start_time','start_date', 'start_hour_of_day','start_day_of_week', 'start_month', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_time', 'duration_sec', 'duration_in_minute', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_share_for_all_trip'. Some wrangling steps executed on the dataset includes; removing null values, changing datatype of start_time from object to datetime  as well as tidying up the dataset by generating new columns which are helping in generating better inights from the data



## Summary of Findings
> The findings were generated n different sections constitutes Univariate, bivariate and multivariate analysis. From the univariate analysis,
one can say the were more trips on weekdays (Monday through fridays) than at the weekend (saturday and sunday) and the peak times of rides were between 8am and 5pm. It was also realised that the most users were subscribers and very few persons were not subcribers and Male riders outnumbered female riders. Majority of the users were young person between the gae 25-40 and very few riders whose ages were above 40. majority of the rides last about 5-10 mins with very few lasting up to an hour. i did perform some data transforming on the data to achive this visualizations by creating new columns with start time as demonstrated at the begining of the analysis.
The was an unusaul distribution in the members age as there were members with age of  140. this age isnt realistic as a 140 year old can't possible ride a bike, therefore there was a need to adjust the column to limit the age to 70 that look more realistic.

> From the bivariate analysis, most of the biplots were done on the usertype against other parameters. from the visualizations, its clear There is significantly more subsribed users compared to users who are customers. Subscribers and customers have distinct behavior patterns when it comes to riding. Most trips taken by subscribers are on weekdays during peak hours for commuting, while customers tend to ride for leisure on weekends in the afternoon or early evenings. Subscribers are slightly older and tend to take longer rides on average compared to non-subscribers. It's worth noting that subscribers who were ilustrated to be slightly older on average , take shorter and faster rides compared to customers. There is a significant difference in the length of trips taken by customers and subscribers. with customer trips considerably shorter that subscribed users.

> The multivariate exploration allows for the simultaneous examination of multiple variables and provides additional information, which improves the identification of patterns previously observed in bivariate and univariate studies. Male users tend to use the service more often than female users, and subscribers tend to use the service more on weekdays, possibly for work commutes. On the other hand, non-subscribing customers exhibit a more relaxed pattern of usage, using the bike-sharing system mostly on weekends and in the afternoons for leisure purposes.



## Key Insights for Presentation

>How distributed are the user type within the dataset?
plot constructed reveal almost all the riders are subcribers (~160000) with only less than 20000 being customers

> How distributed are the rides amongst the days of the week?
Plot shows Thursday has the highest number of rides recorded followed by tuesday with  Saturday and Sunday having the least rides so it makes sense to have more bike on Thursdays than on sundays

> How does user type vary across the days of the week?
Plot constructed for data demonstrates that there are more users who are subcribers than just ordinary customers and the bar charts reveal they ride more on week days than on weekends. Unlike users who are just ordinary customers do not have a clear pattern of when they preferably ride. One can not say for sure what cause this patterns but i guess the reason why there are more subscribed customers is because the subcription deals are perhaps better that ordinary customer deals and people preferably use ride the bikes to work.

