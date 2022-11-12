# Surfs Up Temperature Analysis

## Overview of Analysis

Mr. Avy has asked us to look at the months of June and December, specifically the temperatures in both months, to help him determine whether or not to invest in the surf shop.  Presumably, he assumes that the month of December might be the coldest to look at and June the warmest for Hawaii.  Another consideration might be that both are popular times for people to vacation and he wants to determine if weather might hamper attracting tourists to visit the surf shop.

**The purpose of the analysis is to look at the summary statistics for June and December temperatures and describe additional analysis that could be done to assist W.Avy in his decision**

## Results

There are some interesting insights when comparing the temperatures of June and December:
- The average temperature of each month are close to one another.  December's average temperature is 71 degrees and June's is 75.  December is not, on average, that much colder than June, which implies people are as likely to surf in either month if temperature is the main factor in making that decision.
- The maximum temperature of both months is nearly identical: June max temp is 85 compared to December's 83.  It can be just as warm from month-to-month, but neither month is extremely hot which means that people are likely to spend much more time outdoors.
- The standard deviations of both months are also very similar.  This implies the variation in temperature day-to-day is about the same each month; the caveat is that, because December's average temperature is lower than June's, December's temperatures tend to be lower overall compared to June's.
- The first quartile temperature for December is 69 degrees.  Even though the lowest temperature in the data set is 56 degrees, one could expect most days in December to stay above 69 degrees.

## Summary

Comparing the two months, I would argue that December and June have very similar temperatures, with the occasional colder day possible in December.  This implies that the weather should allow people to surf year-round, with the possibility the surge shack is closed one or two days in the winter months for those unusually cold days.  It also implies that summers should be fairly comfortable and there won't be any unbearable heat driving surfers indoors.

We should look at a few other points of interest in the data before making the final decision:
1. Repeat the queries but also filter on individual monitoring stations to look at whether or not there are significant differences based on their locations.  For example, a station in the mountains might be significantly cooler than one on the beach or in dense foliage.  Since we know that the shack will be on the beach, if we remove those stations with higher or lower elevations, we might get a more accurate picture of actual temperatures we would experience.
2. Aggregate the data into weeks and look for weeks in late December that might be much colder than the earlier portion of the month.  Living in Florida, we know that typically the last week of December is significantly colder than the earlier part of the month.  This might be the period of time that is bringing the entire monthly average down for December versus June and, if this coincides with the slow season since it is unusually cold, we could shut down the surf shop that week and save on labor costs.
