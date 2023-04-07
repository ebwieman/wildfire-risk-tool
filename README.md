# wildfire-risk-tool

## Abstract

## Motivation and Question
Climate change has increased the likelihood of a variety of extreme weather events, including wildfires. These wildfires pose risks to both human and ecological communities. In this project, we plan to use two datasets to predict wildfire likelihood and wildfire area given meteorological data. Our first dataset, the Algerian Forest Fires Dataset, contains fire and non-fire events with 11 attributes that describe weather characteristics at the time of that event. Our second dataset, the Forest Fires Dataset, contains data from Montesinho National Park, Portugal. This dataset contains many of the same weather characteristics as the Algerian dataset, but contains only fire events. Rather than using this dataset to predict whether a fire occurred in a given area, it can be used to predict the size of a fire. We propose to create two wildfire prediction models, one that is trained and validated on the Algerian dataset to predict whether or not a forest fire will occur given certain meteorological conditions and another that is trained and validated on the Portugal dataset to predict forest fire area given many of the same features. Rather than developing our own algorithms, we are planning on using existing models such as Random Forest and SVM and spending our time focusing on model and feature selection. After training and validating our models, we will examine feature importance across models, asking if the same features are most important in determining both wildfire risk and size. Being able to predict wildfire risk and size of areas has a variety of useful applications, such as resources management in protected areas/national parks and planning wildfire mitigation strategies.

## Planned Deliverables

## Resources Required

## What You Will Learn

## Risk Statement
We need to be wary of overfitting our models; the size of our datasets are a big factor. We will be training models on small datasets which means that it will be difficult to avoid training a model that has limited application beyond the specific geographic range represented in the Portuguese or Algerian forest fires datasets. We should keep this in mind instead of trying to achieve perfect predictive and classification accuracy, no matter the cost. Additionally, while we have many features relating to weather and climate in our dataset, there are other important features that are not represented in the data: what species of trees are native to the region, what the density of undergrowth is on the forest floor, if the region is grazed by animals, soil pH, and more. It’s possible that these are just as significant as weather and climate in causing forest fires, and the absence of these data could hamper our ability to train accurate models.

## Ethics Statement

## Tentative Timeline

## 
