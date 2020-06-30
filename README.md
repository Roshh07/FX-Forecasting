# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Capstone: EUR/USD Forecasting

**by: Roshan Khemlani | SG-DSI-14**

## Introduction

The objective is to build a classification model to predict the presence of West Nile Virus.

## Problem Statement

To create a model to predict the presence of West Nile Virus(WNV) based on geospatial and weather information and identify the most important influencing features in Chicago, Illinois.

## Target Audience and Evaluation Metrics

This model is targeted at Chicago City health officials, as it will help them identify hotspots where carriers of the West Nile Virus may see a spike in populations, or even take preventive or preemptive actions to curb the growth of WNV carriers.

**Recommendations**

For our modeling, we found a few disparity between the train and test datasets. The train dataset has only 10506 entries, compared to the test dataset which has 116293 entries. It will be better for our modeling if we can acquire more data for the training dataset.

Based on our EDA, `nummosquito` information appears to be helpful for our prediction. However, we are unable to use it as the test dataset did not have the `nummosquito` information.

Finally, none of the traps in the test dataset is affected by spraying activity. This makes it difficult to ascertain the impact of spraying on predicting West Nile Virus.

In addition, we see that the location is a strong predictor. Additional geospatial information like human density or city zoning information may help us understand better why certain WNV carrying mosquitos species tend to breed at certain parts of the city and what might be contributing to the favorable environment.

Lastly, further study can be conducted on the methodology of spraying. Based on our EDA, the impact of spraying on mosquito population in the locality is inconclusive. Further studies on the frequency of spraying or how city workers perform the spraying, i.e. walking a circle around a block or a team approaching the block from multiple directions, can help improve the effectiveness of spraying and curb mosquito population, and by extension, West Nile Virus transmission during the summer months.



