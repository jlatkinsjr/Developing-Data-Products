---
title       : Calculating Statistics on Life Expectancy and Death Rate
subtitle    : in Virginia during the 1940's
author      : Joseph Atkins
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction & Background

The "Calculating Statistics on Life Expectancy & Death Rate" shiny application is designed to calculate statistics about the life expectancy and death rate in Virginia during the 1940's.

# Data Documentation
The application uses historical data provided by the American Sociological Review. The life expectancy and death rates are cross-classified by age group and geographic location. The geographic locations are as follows: Rural and Urban. The cross-classifications are: Rural Male, Rural Female, Urban Male, and Urban Female. 

Below is a sample of the data output. 

```
##       Rural Male Rural Female Urban Male Urban Female
## 50-54       11.7          8.7       15.4          8.4
## 55-59       18.1         11.7       24.3         13.6
## 60-64       26.9         20.3       37.0         19.3
## 65-69       41.0         30.9       54.6         35.1
## 70-74       66.0         54.3       71.1         50.0
```


---

## Life Expectancy

The application has the ability to calculate the following statistics around life expectancy by geographic location and gender:

* Number of Deaths by Age Group

The age groups are as follows: 
* 50 - 54 years old
* 55 - 59 years old
* 60 - 64 years old
* 65 - 69 years old
* 70 - 74 years old


---

## Death Rate

The application has the ability to calculate the following statistics around death rate by geographic location and gender:

* Average Number of Deaths 
* Median Number of Deaths
* Standard Deviation of Deaths

Also displayed is a summary breakdown of the data by quarter.

---

## Example of Visual Statistics

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

---

## Summary

The application is useful to chart differences in the death rate of male versus female and urban versus rural geographic locations.

The visual display as a dot chart provides a clear view of trends while pin pointing the exact number for analysis. 

The calculated statistics provides a base point for a better analysis of the data.

The purpose of this application is to provide users with the ability to research and analyize the life expectancy and death rates in Virginia during the 1940's.





