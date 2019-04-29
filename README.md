# Mod 5 Project

# Beer-Recommendations
Beer Recommendation System. Final Project for Flatiron School.

## Motivation
Everyone enjoys a good drink, but what is a good drink? Everyone has different tastes and preferances. My goal was to create a beer recomendation system so that people don't have to waste time and money trying beer that they don't like, and are more apt to try something new that they will enjoy based on past preferances.  

## Sources
Data from BeerAdvocate.com 

## Exploratory Data Analysis 
This shows the amount of reviews by beer type in the dataset: 

![image of spreadsheet](/readme/OxfordPetData.png)

## Data Organization 
After EDA, the data had to be reshaped to be able to work with surprise.

## Best Model Results
Our best performing model had a tvalidation accuracy and a test accuracy score of 88%. We used transfer learning and stacked two CNN models on top of each other (VGG19 and Resnet50). However this model took a long time to run and would crash colabs from using too much RAM.

![image of best model outcomes](/readme/BestModel.png)

## Model Results
Given the computing power problems we actually perfer our second best model as it has a validation accuracy score of 83%, only took 10 minitues to run and doesn't crash Colabs. This model uses InceptionV# with weights as the base model.

![image of next model outcomes](/readme/imagenet2_testcm.png)

![image of next model outcomes per epoch](/readme/validation.png)

## Frameworks / Libraries Used:
- Surprise! 
- BeautifulSoup
- Sklearn
- Matplotlib
- Pandas
- Numpy
- Itertools
- Scipy 
- Random
- os
- shutil 
- re

## Credits
By Lois Rosenbloom 
