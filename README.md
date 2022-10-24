# Udacity-Data-Wrangling

## By Elkhaddouri Ayoub

## Skills
- Exploratory visualizations with matplotlib and seaborn libraries: countplot, hist, scatter, pairplot, boxplot, barplot.

## Dataset
- The dataset you will be processing (and analyzing and visualizing) is the archive of tweets from Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. But the numerators? Almost always higher than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're Brent dogs". WeRateDogs has over 4 million subscribers and has received international media coverage.

## Overview of the project steps

Your tasks in this project are as follows:

- Step 1: Data collection

- Step 2: Data evaluation

- Step 3: Data cleaning

- Step 4: Data storage

- Step 5: Analyze and visualize the data

- Step 5: Analyze and visualize the data

### Workflow

I gathered the data from three different sources, I used the document that exists in udacity because my developer account was not approved by twitter.

Then I explored each dataset to understand the context of the dataset then I looked at the data and I noticed several things, for example (order issues and quality issues), some data was extracted incorrectly, many columns were formatted incorrectly and some column types did not match the data type, and I did not understand the meaning of some columns, and to fix this I searched several sources to understand them.

In this exploration step, I noted all the problems I find so I started to fix all the problems,

I started with quality issues like fixing the type of some columns (object to float, object to bool, object to datetime ect), and dealing with missing values, duplicate data, data formatting, etc.

then I went to the problem of order the deletion of columns, join between tables ect.. Finally to correct the data I created other columns, I deleted others ect.

After correcting the data, I decided to join the three datasets to create one set and explored the data one more time to find relationships between the data and noted questions and answered them with a simple and clear visualization.

In the last step, I used a lot of visualization (scatterplot to see the relationship, bar chart to see the percentage, line chart to see the evolution in time). At the end I wrote this report that describes what I did in this project

## Summary of Findings

- from this analysis we can say that there is a very important evolution of the number of retweet, favorite and rating in time there is also a small correlation between them. we can also see that the majority of people really like a certain type of dog and detect certain types



## Files:

- act_report.ipynb: notebook with the exploratory data analysis.
- act_report.html: exploratory data analysis in html.
- wrangle_act.ipynb: notebook with the report data analysis.
- wrangle_act.html: notebook with the report data analysis.
- wrangle_report.ipynb: notebook describes wrangling efforts.
