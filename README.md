# wildfire-risk-tool

## Abstract

Our project will address the capacity of machine learning models to understand forest fires in two different areas. We will first predict the area of different forest fires occurring in Portugal by selecting and applying a model to a University of California Irvine dataset, and then use a dataset detailing fires in Algeria to predict the likelihood of fires occurring. We will train and validate our area prediction model on the Portugal data, and apply it to the Algeria dataset, following an unsupervised workflow. To execute this project, we will research different models that help predict natural hazards like forest fires before selecting and applying one, and review past studies, such as Coretz and Morais, to inform the direction of our analysis. Finally, we write a paper outlining the ethics and implications of relying on machine learning algorithms to predict natural hazards. 

We will consider this project a success if we successfully train two machine learning models to predict expected area of fires in Portugal and the likelihood of fires in Algeria, and are able to apply these models more broadly. This success depends on conducting a review of prior studies, exploring our datasets, researching and selecting an appropriate model, and writing/reflecting on using computers for predicting natural disasters and risk. 

## Motivation and Question
Climate change has increased the likelihood of a variety of extreme weather events, including wildfires. These wildfires pose risks to both human and ecological communities. In this project, we plan to use two datasets to predict wildfire likelihood and wildfire area given meteorological data. Our first dataset, the Algerian Forest Fires Dataset, contains fire and non-fire events with 11 attributes that describe weather characteristics at the time of that event. Our second dataset, the Forest Fires Dataset, contains data from Montesinho National Park, Portugal. This dataset contains many of the same weather characteristics as the Algerian dataset, but contains only fire events. Rather than using this dataset to predict whether a fire occurred in a given area, it can be used to predict the size of a fire. We propose to create two wildfire prediction models, one that is trained and validated on the Algerian dataset to predict whether or not a forest fire will occur given certain meteorological conditions and another that is trained and validated on the Portugal dataset to predict forest fire area given many of the same features. Rather than developing our own algorithms, we are planning on using existing models such as Random Forest and SVM and spending our time focusing on model and feature selection. After training and validating our models, we will examine feature importance across models, asking if the same features are most important in determining both wildfire risk and size. Being able to predict wildfire risk and size of areas has a variety of useful applications, such as resources management in protected areas/national parks and planning wildfire mitigation strategies.

## Planned Deliverables

## Resources Required
Thankfully, much of what we need, we already have. We have a dataset for forest fires in Algeria (https://www.kaggle.com/datasets/nitinchoudhary012/algerian-forest-fires-dataset) which we will use to train a model classifying whether or not fires occur, and we have a dataset for forest fires in Portugal (https://archive.ics.uci.edu/ml/datasets/forest+fires) for which we will train a model predicting total burned area. Other than this, because these datasets are not very large the computing power available on our personal computers should be sufficient for training, testing, and experimentation.

We also want to find meteorological data for the whole US to see if we can predict areas most at risk for forest fires. Finding this data may be challenging, and it also has the potential to be computationally expensive as this is a very large area to find data for.

We also will need to explore background literature and academic studies relating to the use of Machine Learning in exploring/predicting natural hazards, especially wildfires. One aim of our project is to explore the applications of ML to ecological/environmental conservation and protection, so finding academic resources relating to this topic is important.


## What You Will Learn

## Risk Statement
We need to be wary of overfitting our models; the size of our datasets are a big factor. We will be training models on small datasets which means that it will be difficult to avoid training a model that has limited application beyond the specific geographic range represented in the Portuguese or Algerian forest fires datasets. We should keep this in mind instead of trying to achieve perfect predictive and classification accuracy, no matter the cost. Additionally, while we have many features relating to weather and climate in our dataset, there are other important features that are not represented in the data: what species of trees are native to the region, what the density of undergrowth is on the forest floor, if the region is grazed by animals, soil pH, and more. It’s possible that these are just as significant as weather and climate in causing forest fires, and the absence of these data could hamper our ability to train accurate models.

## Ethics Statement

## Tentative Timeline

## 
