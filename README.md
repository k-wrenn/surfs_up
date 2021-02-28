# surfs_up
## Project Overview
Wanting to open a surf and shake shop on the island of Oahu but in need of investors, The purpose of this project is to analyze weather data for the island becuase W.Avy, the investor, has concerns due to similar past business ventures that failed due to weather. 

In order to determine if the shop will be sustainable year-round, W. Avy requested we look at temperature data for specifically for the months of June and December in Oahu. 

## Resources
Data: hawaii.sqlite

Software: SQLite SQLAlchemy, Python, Jupyter Notebook

## Results

* On average, tempuratures on Oahu are about 4 degrees higher in June than in December (74.9 and 71.0 respectively)

* The standard deviation of December tempuratures is greater, which means there is more variation in tempurature in December than in June .

* The high temperatures for both months are pretty similar (83 in December and 85 in June), however there is a considerable differnce in low tempuratures (56 in December vs 64 in June). This means June weather may be slightly more predictable whereas December temperatures are not.

## Summary
Although W. Avy only requested we examine the temperature data for June and December, it may be worthwhile to also look at the precipitation during those months as well. Not many people would be out surfing in thunderstorms! This infomation would be beneficial in determining whether or not to keep the shop open all year. For instance, if most days in December are rainy and days in June are sunny, it may not be practical to keep the shop open in December, even though the above analysis showed that temperatures are, on average, almost as warm as June.

Another thing to consider, but was not included in our data set, is wind speed. Too windy may prove difficult for many surfers. Strong winds also may not be ideal for ice cream eaters either, it might blow the scoop right off the cone!

Lastly, it may be beneficial to do an analysis on prior surf reports of Oahu. Surf reports include valuable information for surfers, such as wave height, wind direction, swell direction, and tide. If Oahu does not have many favorable surf reports, it may not draw the surf crowd the shop hopes. 
