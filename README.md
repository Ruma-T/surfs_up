# surfs_up

###Overview of the analysis: 

##Explain the purpose of this analysis.

To start a new business, investors want to find out the temperature data for the months of June and December in Oahu. Analyzing detailed information about the summer and winter season, they can decide whether surf and ice cream shop business is sustainable throughout the year in Oahu.
To help the investors, we need to add the dependencies and connect the SQLite database which is stored locally, and it will help us move more quickly through the analysis.
 I wrote a query that filters the date column from the measurement table to retrieve all the temperatures for the month of June and December. Using the session query function, I run the queries in SQLAlchemy then created a DataFrame. To get the statistical details like mean, standard deviation, max, min  used describe function with Panda.
 
Results: 

June

o	The maximum temperature in June is 85 degrees

o	The minimum temperature in June is 64 degrees

![png_Mod9ch1](https://github.com/Ruma-T/surfs_up/blob/main/Resources/Mod9ch1.PNG)


December

o	The maximum temperature in June is 83 degrees

o	The minimum temperature in June is 56 degrees

![png_Mod9ch2](https://github.com/Ruma-T/surfs_up/blob/main/Resources/Mod9ch2.PNG)


Summary: 

•	The standard deviation shows that the difference of temperature from mean is 3.25 and 3.75 respectively for June and December. Mean temperature is 75 and 71 degrees respectively for June and December. So, there is not a big temperature difference between summer and winter specially in June and December.

•	We can use similar code to see the precipitation rate for June and December and the record shows below:

![png_Mod9ch3](https://github.com/Ruma-T/surfs_up/blob/main/Resources/Mod9ch3.PNG)



![png_Mod9ch4](https://github.com/Ruma-T/surfs_up/blob/main/Resources/Mod9ch4.PNG)



