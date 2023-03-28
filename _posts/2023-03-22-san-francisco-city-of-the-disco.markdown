---
layout: post
title:  "San Francisco crime rate analisys"
date:   2023-03-22 10:22:44 +0100
categories: jekyll update
---

# The picture of the most likely crime in San Francisco
San Francisco is a commercial, financial, and cultural center of Northern California. The city proper is the fourth most populous in California, with 815,201 residents as of 2021, and covers a land area of 121 square kilometers, making it the second most densely populated large U.S. city after New York City.

In terms of safety, according to [Numbeo](https://www.numbeo.com/crime/in/San-Francisco) the Crime Index is 61.14/120 which rates the Level of crime as <span style="color:#9B1E1B">High</span>. <i>(as per 22 mar 2023)</i>

In this post we are going to dive into the nature of those crimes, the time and the place where those crimes were committed in order to get the picture of a most likely crime in San Francisco.

I am going to use the public statystics data from [https://datasf.org/opendata/](https://datasf.org/opendata/). The data below represents police incidence reports from 2003 to may 2018

First, by studying the amount of each type of crime, we can conclude that approximately half of the crimes are related to <b>theft</b>, which makes it the most often committed crime in San Francisco.


<embed
       type="text/html"
       src="/pie_chart.html"
       width="920"
       height="550"
       >

Next, let's analyze the time and the day of the week of the Larceny/theft crimes.

The next graph represents the number of thefts reported to the police per hour of the day and each line represents a different day of the week. Select each line and compare the frequency. 

From the graph it's clear that most often these crimes are commited on <b>Fridays, around 19 o'clock</b>.

<embed
       type="text/html"
       src="/bokeh.html"
       width="850"
       height="650"
       >

Lastly, we have to look for the district from San Francisco where the most thefts are made. Using the data from the datasf site I created a map of San Francisco's districts and color each district according to the amount of thefts made.

From the map one can spot that <b>the district of the Southern police departament</b> has the highest number of thefts reported.

<embed
       type="text/html"
       src="/map of SF.html"
       width="800"
       height="600"
       >

In conclusion, the most common crime in San Francisco is a guy stealing a mobile phone on a friday evening in the Southern district. I hope you liked this little experiment :)

![demo image](/img/image2.jpg)