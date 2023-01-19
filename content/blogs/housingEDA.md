---
title: "Exploratory Data Analysis on housing data"
date: 2023-01-18T18:17:19+05:30
draft: false
author: "Vadiraj Adabaddi"
tags:
 - "Data Wrangling"
 - "Data Analysis"
 - "Data Visualisation"
 - "Feature Engineering"
 - "Pandas"
 - "Seaborn"
 - "Matplotlib"
image: /images/real-estate-post.jpg
---
### 🔗 [GitHub](https://github.com/Vadiraj-13/housing-EDA)

In which Indian city, the flats are most expensive?

## Description:

A data analysis and visualisation was performed on a housing dataset to find out which city has the highest median cost per sqft with respect to flats.

The dataset has around 14000+ rows of data having properties from various Indian cities like Chennai, Mumbai, Bangalore, Delhi, Pune, Kolkata and Hyderabad.


Technology used: **Numpy, Pandas, Matplotlib and Seaborn**

## Results:
![Result](/housingresult.jpg)

1. The median of price per sqft is much higher in Mumbai compared to other cities.
2. Also the boxplot of Mumbai is more spread out when compared to other cities which are comparitively tighter. This indicates Mumbai has wider range of values of price per sqft when compared to other cities.

The median values for various cities are as follows: 
| City      | Median |
| ----------| ----------- |
| Bangalore     | 5571.0             |
| Chennai       | 5550.0             |
| Hyderabad     |     5774.5         |
| Kolkata       |     4211.0         |
| Mumbai        |        17273.0     |
| New Delhi     |      7301.0        |
| Pune          |      5714.0        |
| Thane         |      9006.0        |

