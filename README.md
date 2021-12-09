# PDP
Personal Data Project

Motivation: I wanted to find out how the amount I run correlates to how much I eat and how much sleep I get, and I wanted to see if there was a correlation between the sleep and eating as well.

Data Process:  I collected the sleep data and the running data through a Garmin Forerunner 235 watch and the Garmin Connect app.  I collected calories eaten through the MyFitnessPal app which connects to the Garmin Connect app.  I would make sure to track everything I ate throughout the day and to track every run I went on as well as making sure to wear the watch to sleep every night to make this data as accurate as possible. I did remove the month of September because I was sick during the whole month and being sick would have had no running with lots of sleep and not as much eating, so the data would have been skewed.  I also removed the days where I did not run because it skewed the data with lots of points being at 0 distance ran and it messed up the regression.


Visualization: This is a graph showing the amount of distance I ran per day on the x-axis with the amount of food I ate on the y-axis.  The line through the middle of the data is a line of best fit.  It is showing the correlation between the distance ran and the amount of food that I ate throughout the day. 

![Data_115PersonalDataProject](https://user-images.githubusercontent.com/91585746/145490068-183eec51-6173-4405-8445-a72abda06fa0.jpeg)


Analysis: I did a linear model regression with distance ran in kilometers as the x-value and the amount of food eaten in kilocalories on the y-axis.  I found that the equation for the line of best fit was kCal = 1438.39 + 148.61(KM) with the coefficient of determination being 0.7213455.  So, the relationship between distance ran and food eaten was somewhat linear.  It became much more linear after the days with no distance ran were removed.


