# Bikesharing Analysis


## Overview:


In this analysis, citibike user data from New York City was used to create visualizations in Tableau.  First, the original csv file was updated using pandas in Jupyter Notebook to change the Trip Duration column to a Datetime Format that could be used in the analysis.  Then worksheets were made in Tableau, displaying bike checkout times for users, checkout times by gender, trips by weekday per hour, trips by weekday per hour by gender,  trips by weekday per gender, August peak hours, and gender breakdown of all users.  After the worksheets were completed, they were compiled in a Tableau story.

[link to dashboard](https://public.tableau.com/app/profile/corinne.hume/viz/NYCCitibikeAnalysisStory_16236060852970/Story1)
## Results:


### Checkout Times for Users:


This line graph displays the amount of time all users rented their citibike in minutes on the bottom x-axis and hours on the top x-axis.  The number of users is displayed on the y-axis.  The graph shows most users checkout their citibikes for 5 minutes with a total of 146,752, and most bike checkouts are for less than 60 minutes.  

![checkout_time](https://user-images.githubusercontent.com/78699521/121812977-ecde2a00-cc1e-11eb-886f-79498d7f3402.png)


### Checkout Times by Gender:


The following visualization displays user checkout times separated by gender, female, male or unknown.  Males have the most checkouts in the upto 50 minute range, especially for checkout times for 5 minutes.  Females have the second most checkouts, peaking at 6 minute checkout times.  Unknown genders have the least checkouts in the first 60 minutes, with a similar number of checkouts in the 5 to 25 minute range. After 60 minutes Males, Females and Unknowns have a similar number of checkouts for longer checkout times. 

![checkout_time_by_gender](https://user-images.githubusercontent.com/78699521/121812986-f5366500-cc1e-11eb-8402-a152618915d5.png)


### Trips by Weekday per Hour:


The heatmap below displays the number of bike trips by hour per weekday.  Green represents fewer bike checkouts, and red the most bike checkouts.  The maximum number of trips occur at 6pm on Thursday evenings.  In general, the most bike checkouts occur M-F around 8am and between 5-7pm, and on Saturdays between 10am and 7pm.  Wednesday and Sunday have fewer bike checkouts than other weekdays.
![trips_by_weekday_hour](https://user-images.githubusercontent.com/78699521/121813005-0aab8f00-cc1f-11eb-82af-7c29782150c8.png)


### Trips by Gender (Weekday per Hour):
Male and Female trips per weekday are similar to trips by weekday per hour for all users.  Unknown gender users have fewer bikecheckouts on weekday mornings and a similar number of bikecheckouts throughout the day M-F, unlike Male and Female users that have fewer checkouts during the midday and more at 8am and 5-7pm.  

![trips_by_weekday_gender](https://user-images.githubusercontent.com/78699521/121813011-1303ca00-cc1f-11eb-8239-70e15ead221e.png)


### User Trips by Gender per Weekday:
Unknown gender riders are the most prevalent single use costumers for bike checkouts during the week compared with male and female users.  Male and female users are most likely subscribers.  Males have the most subscribers on Thursday and the fewest on Sunday, Wednesday, and Saturday. 

![user_trips_by_gender](https://user-images.githubusercontent.com/78699521/121813027-2878f400-cc1f-11eb-895b-b4fbfd6c6fd2.png)


### August Peak Hours:
In August, the most bikecheckouts occur at 5pm, followed by 6pm and 7am.

![august_peak_hours](https://user-images.githubusercontent.com/78699521/121813034-2fa00200-cc1f-11eb-8c22-4f7ebb20bed7.png)


### Gender Breakdown:


![gender_breakdown](https://user-images.githubusercontent.com/78699521/121813043-375fa680-cc1f-11eb-9bb6-6e89dd2fa9dd.png)




Summary:

