# Module 1 Final Project
Team Members: Dipta Roy and Muriel Kosaka

## Introduction

In this final project, we have been given the scenario of Microsoft expressing interest in creating movies and our team has been tasked to help them better understand the movie industry. By exploring films from 2018 and 2019, we analyzed factors that attributed to its success at the box office. After which we must present our findings and make recommendations to Microsoft to aid in creating profitable films. 

## Questions that we aim to answer during this project

![Pyramid](/data/Pictures/pyramid.png)

## Process

1)	See **BoxOfficeMojo_DataScraping.ipynb**: Here we web scraped Box Office Mojo for movies from all seasons (Fall, Spring, Summer, Winter, and Holiday) for 2018 and 2019 and created necessary Data Frame’s for analyses.
2)	See **Data_Visualization_years_correlation.ipynb**: We then merged this DataFrame with zipped data files that were provided to us to answer our first two questions.
3)	See **Data_Visualization_Season_summer**: We found that movies shown during the Summer and Holiday season had the highest average gross
4)	see **Data_Visualization_Season_summer** and **Data_visualization_holiday_season**: For each season, we answered questions four and five.

## Libraries

   Data Collection:
        - Requests
        - Beautiful Soup
        - Pandas
    
   Data Cleaning and Visualization:
        - Matplotlib
        - Seaborn
        - Pandas


## Findings and Suggestions

    Even though movies were not doing well for 2019, we believe this is reason to investigate further what ways to improve movies to generate high gross. There was a slight positive correlation between production budget and gross indicating that the more money spent on production, the higher gross, total gross, and worldwide gross earned for a given film. Films shown during the summer and holiday season generated the highest average gross, therefore we suggest that films be shown in theaters during those times. Upon further analyses of genres and movie length, we recommend that films shown in the summer should be of the Action and Adventure or Comedy and Musical genres and should have a runtime of at least 120 minutes. We also recommend that films shown during the holiday season should be of the Animation and Comedy or Comedy and Family genres and should have a runtime of at least 120 minutes to generate high average gross. 

