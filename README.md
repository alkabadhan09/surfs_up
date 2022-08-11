# surfs_up
## Overview

### Background
In the Module, in order to open my own business of selling surfboards and ice cream to locals and tourists in Hawaii, I meet up with an investor called W.Avy. He asks me to analyse a weather dataset from the island of Oahu. I use SQLite and SQLAlchemy in order to analyze the precipitation levels from the previous year in order to W.Avy that Oahu is a perfect place to open up the surf n' shake shop.

### Purpose
W. Avy wants more information about tmperature trends in the months of June and December in order to determine if the business is sustainable year-round. In the challenge, temperatures for June and December are extracted from the SQLite dataset using SQLalchemy and .describe() is used to print out the temperature summary statistics for the June and December DataFrame.

## Results
![June_temps](https://user-images.githubusercontent.com/107225715/183990812-f603ac2e-d934-4c69-b7f4-3428f4d5463a.png)
![Dec_temps](https://user-images.githubusercontent.com/107225715/183990842-f2f2a4c8-625d-43fa-9fb7-0d92dbdc1094.png)

* The count for June and December is 1700 nd 1517 respectively. This is not a huge difference between the size of data points for these two months, which means the data is reliable and can be used for our analysis. 

* The mean for June and December is 74.94 and 71.04 respectively, which does not convey a huge difference in temperatures during these months. 

* The standard deviation of both June and Decemeber Temperatues are around 3.26 and 3.75 which is not a big difference. Smaller STD indicates that the data mostly centers around the mean, which means there is not a lot of variation in temperatures during these months.

## Summary
![June_box](https://user-images.githubusercontent.com/107225715/184211671-5e69bc05-3ce3-4ff5-aab1-71f9ceb441fd.png)
![dec_box](https://user-images.githubusercontent.com/107225715/184211715-fb8e9bd2-2a83-4a24-94f6-c3c613ec0826.png)

From our statistical summary charts, we can see that there is not a major difference between the June and December temperatures. The STD is 3.25 and 3.75 for June and December which means there is not a lot of variation between the temperatures. In december, temp can go as low as 56 but we can assume that it can be during nighttime. From the boxplots above, we can see there are no outliers and the data revolves around the median for the most part. From all this, we can conclude that the Surf n' Shake business will do well in the island year-round.


