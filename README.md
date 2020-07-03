# Nashville-Traffic-Accidents

## INTRODUCTION:
I am presenting about what features lead to higher and lower injury or fatality rates among car accidents.

## OBJECTIVE:
To do EDA and test different classification models to determine which features have the most positive or negative influence on injury or fatality. I want to reduce the amount injuries and reduce the number of lives lost due to traffic accidents.

## THE DATASET:
Metro Nashville Police Department data sourced from Socrata Open Data API.

## SKILLS REQUIRED TO COMPLETE:
The skills used to complete this project consisted of sourcing date by API, data cleaning, EDA, Feature Engineering, Feature Selection, Class imbalance, model selection based on F1 scores and using Python to make visualizations with Pandas.

## WHAT I POSTED ON GITHUB:
There are three notebooks posted on Github. The first consisted of data cleaning and EDA. The second consisted of a map of traffic accidents. The third consisted of additional EDA and model testing classification evaluation. Lastly, the ReadMe which is a layout my project.

## QUESTIONS I POSED:
1. What are the features that positively or negatively affect probability of getting injured or killed in a traffic accident?
2. Does weather have an affect?
3. Does the type of collision have an affect?
4. Do month, day of week or hour of day have an affect?

## HOW I PUT OUR DATA TOGETHER:
First, I made on API call on the Metro Nashville Police Department data sourced from Socrata Open Data API. After we gathered the data, we then selected the top 17 networks that had aired the most shows. Next, we took the vote average for each of the 17 networks. Following that, we compared runtime with vote average to see if there was any correlation between the two. Finally, we compared the TV show’s genre with IMDB rating from web scraping.

## FUTURE/STEPS I WOULD HAVE DONE
1. Remove hit and run feature as it is an event that takes place after the accident occurs.
2. Investigate feature importance from xgboost (latitude and longitude), which were dropped from the logistic regression model.
3. Distinguish between accidents without injury and  death vs with injury or death in Folium,
4. Get a national dataset with more features relating to vehicle and driver
5. Try different resampling methods
6. Incorporate interacts among the features


## RECOMMENDATIONS
Based on the fact that the highest positive affect on injury or fatality was "single vehicle collision" in the collision type feature, I would recommend crash avoidance systems leading up to self-driving technologies.


## PRESENTATION LINK:
https://docs.google.com/presentation/d/1SsFSUOURUnbo6AjTIF0NUPqqf-Whgp2DTrux_G4WcYQ/edit#slide=id.g808e4a1cc6_0_325

## IMAGE REFERENCE
https://www.trolleytours.com/nashville/2-day-itinerary
