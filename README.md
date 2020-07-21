# Nashville-Traffic-Accidents

<img src="images/Picture%20of%20Nashville.jpg" width="650">

## Introduction:
I am presenting about what features lead to higher/lower injury or fatality rates among car accidents. My interest in self-driving cars lead me to this topic.

## Objective:
To do EDA and test different classification models to determine which features have the most positive or negative influence on injury or fatality. These results can be used to reduce the amount injuries and fatalities due to traffic accidents.

## The Dataset:
Obtained 34,000+ accidents from the Metro Nashville Police Department sourced with Socrata Open Data API. Some of the features included weather, collision type and lighting conditions. Since these features are categorical, I created dummy columns with them. I also did some feature engineering with the datetime feature. I created 'hour_of_day', 'month', 'day_of_week' and 'is_holiday' features from datetime.

## Skills Required to Complete:
The skills used to complete this project consisted of sourcing data by API, data cleaning, EDA, Feature Engineering, Feature Selection, Class imbalance, model selection based on F1 scores and using Python to make visualizations with Pandas.

## Visualization:
This is a map showing the accidents that occured in Nashville in 2018. The green dots represent an accident in which no harm occured. The red dots represent an accident in which an injury or fatality occured.

<img src="images/Map%20of%20Nashville%20Accidents.png" width="950">

## What I Posted on Github:
There are three notebooks posted on Github. The first consisted of data cleaning and EDA. The second consisted of a map of traffic accidents. The third consisted of additional EDA and model testing classification evaluation. Lastly, the ReadMe which is a layout my project.

## Questions I Posed:
1. What are the features that positively or negatively affect probability of getting injured or killed in a traffic accident?
2. Does weather have an affect?
3. Does the type of collision have an affect?
4. Do month, day of week or hour of day have an affect?
5. Which model has the highest F1 score?

## Future Steps:
1. Remove hit and run feature as it is an event that takes place after the accident occurs.
2. Investigate feature importance from xgboost (latitude and longitude), which were dropped from the logistic regression model.
3. Get a national dataset with more features relating to vehicle and driver
4. Try different resampling methods
5. Incorporate interactions among the features

## Recommendations:
Based on the fact that the highest positive affect on injury or fatality was "single vehicle collision" in the collision type feature, I would recommend crash avoidance systems leading up to self-driving technologies.

## Presentation Link:
https://docs.google.com/presentation/d/1SsFSUOURUnbo6AjTIF0NUPqqf-Whgp2DTrux_G4WcYQ/edit#slide=id.g808e4a1cc6_0_258

## Image Reference:
https://www.trolleytours.com/nashville/2-day-itinerary
