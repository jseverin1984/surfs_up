# Surfs Up Surf and Ice Cream Shop

## Overview

I was tasked with analyzing the last 8 years worth of weather data in order to help W. Avey in his decision to open up a new
surf shop on the islands of Hawaii.  I used sqlAlchemy to access the sqlite database and create dataframes of the data needed. Lastly,
I ran a quick statistical analysis on said data in order give a better understanding on the historical weather data and provide W. Avey
with the best information possible to help him make a decision about opening a new business.

## Results

Below I have highlighted "three" key differences in weather between the June and December data. The two images provided, show the statistical
summaries for both June and December.

![alt text](https://github.com/jseverin1984/surfs_up/blob/main/june.png "statistical summary for June")
![alt text](https://github.com/jseverin1984/surfs_up/blob/main/december.png "statistical summary for December")

1. The highest recorded temperature for June was only two degrees higher than December.

2. The average daily temperature for June was nearly four degrees higher than December.

3. June had almost 200 hundred more recorded daily temperatures than December.  This could use further evaluation to make sure the
higher number of recordings is not skewing June's data one way or another. Likewise, December's data may be skewed based off of having
fewer recorded observations.

## Summary

Too summarize, as most would think, it would be better to run an ice cream shop mostly during the summer months when temperatures are
typically at their warmest. But the data shows that in Hawaii, the difference in average daily high temperature does not vary enough to
warrant this. With only a four degree difference, Hawaii seems completely suitable to run and ice cream surf shop year round.

There is also need for more analysis on the weather data that was provided and possibly gathering of more data.  Queries should be made
into how many stations were recording the data, and how many data points each provided. This should be mapped with their location in order
to provide any insight into whether any of the analysis might be skewed based on location of weather readings and how much weight each
station carried on the averages.