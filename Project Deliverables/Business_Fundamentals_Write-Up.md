# Business Fundamentals Write-Up

## Abstract
For this project, I chose to focus on Apple Maps. Specifically, I created a project proposal for a new Apple Maps feature with the intention of increasing Apple Maps market share within the mobile navigation app space. To craft my proposal I performed EDA on a publicly available data set of traffic accidents for the past 3 months in Denver, CO. I called my new feature "safe route", which provides an alternative "safer" driving route option to the app user in addition to the typical "fastest" route already provided by the app. I utilized Google Sheets and Tableau to visualize my EDA findings and presented my pitch in a short slide deck.

## Design
The idea for this project originated from the fact that most my friends are iPhone users yet they are also Google Maps users, instead of using the preloaded Apple Maps that comes with iPhone. Upon investigating further, I found that this preference for Google Maps is not specific to my friend group. I found that Google Maps has 124M monthly unique app users in the United States. Comparatively, Apple Maps has onlny 62M. As an attempt for Apple Maps to increase their market share, I proposed a new feature "safe route". This "safe route" feature would pull data from recent car accidents in a given city and assign a "safety rating" to a road based on things such as number of recent accidents, severity of those accidents, time of day, etc. My theory is that the "safe route" feature would generate consumer demand thereby increasing Apple Map's market share.

## Data
I used the publicly available traffic accident data that the city of Denver provides for free on their open data catalog website. Included in this data set is every polic reported traffic accident that has occurred in Denver including accidents ranging from fender benders, hit & runs to fatal accidents. My analysis for this project focused on traffic accidents from June 2021 through September 2021. The features I looked at for a given accident included type of driving offense, driver cause (e.g. reckless driving), vehicle movement (e.g. turning left), road condition (e.g. wet or dry).

## Algorithms
I did not have time to begin using any algorithms to further develop the "safe route" feature. In the future I would plan to use build a regression model and classification model to investigate which features have the strongest relationship for predicting when an accident happens, and also assigning a liklihood of an accident occuring on a given road.

I used EDA techniques to clean, explore and visualize the Denver traffic accident data set.

## Tools
+ Python to import the data set and perform initial cleaning.
+ Google Sheets to filter, aggregate, explore and visualize the data
+ Tableau to visualize my EDA findings

## Communication
I created a short slide deck presentation to communicate my initial EDA findings and "safe route" proposal, which is available on my GitHub repo.


```python

```
