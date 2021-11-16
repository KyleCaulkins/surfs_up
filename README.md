# Surfs_Up

## Overview

This analysis is part of a broader project, starting a surf and shake shop on the island of O'ahu, Hawaii. A key investor to the surf and shake shop, W. Avy, is concerned about the weather on O'ahu. Specifically, W. Avy is requesting temperature data for the months of June and December in Oahu. The months of June and December are of interest because these two months will indicate if the surf and shake shop is a sustainable year-round business. The following analysis represents the findings from W. Avy's request.

## Results

The following is a list of three significant findings from analyzing the weather data for O'ahu, Hawaii in the months of June and December. Detail of the code used for this analysis can be found
![here.](/SurfsUp_Challenge.ipynb)

* Finding 1
The minimum, maximum and mean temperatures for the months of June and December are of particular importance in this weather analysis. Below are the results from the analysis, with min, max, and mean temperatures highlighted. The month of June has a mean temp of 74.9 degrees, min temp of 64.0 degrees, and a max temp of 85.0 degrees. The month of December has a mean temperature of 71.0 degrees, a min temp of 56.0 and a max temp of 83.0 degrees. These temperatures should be very good for surfing, and warm enough for patrons of the shop to enjoy a shake.

![june_mean](/Resources/june_temp_mean.png) ![dec_mean](/Resources/dec_temp_mean.png)

* Finding 2
It should be noted that the data used for analysis spans several years and has 1700 observations for the month of June and 1517 observations for the month of December. With a data set of this size, the findings are significant. The obersvations are also relatively equal between the two months. A large data set, over several years, and taken from all days in each month, should add confidence in the analysis for W. Avy to make a decision. 

![june_obs](/Resources/june_ob_count.png) ![dec_obs](/Resources/dec_ob_count.png)

* Finding 3
The two months have relatively low standard deviation in temperature. June has a std of 3.26 and December has a std of 3.75. There is only a few degrees of standard deviation within each month, and only a few degrees in difference between June and December mean temperatures. Given this information, the island of O'ahu has a relatively stable temperature.

![june_std](/Resources/june_temp_std.png) ![dec_std](/Resources/dec_temp_std.png)

## Summary

All in all, the temperature of O'ahu should be suitable to attract surfers and warm enough to enjoy a shake. There does not appear to be a huge standard deviation in temperature for the months analyzed, and the min/max temperatures are mild as well. This information should help W. Avy's confidence in investing in a shop on O'ahu. W. Avy has invested in a surf shop that got rained out of business, and does not want to make that mistake again. In order to add further confidence to this investing decision it is recommended that information regarding precipitation, wind speeds, and tides are added to the analysis. A precipitation analysis would likely address W. Avy's concerns directly. The wind speed and tidal information would verify that O'ahu was not too gnarly for the majority of surfers. With the current weather analysis and recommendation, there should be enough information to convince W. Avy that O'ahu is a prime location for an investment. Surf's up dude!
