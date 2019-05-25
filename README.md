# Mod 5 Project

# Beer-Recommendations
Beer Recommendation System. Final Project for Flatiron School.

## Motivation
Everyone enjoys a good drink, but what is a good drink? Everyone has different tastes and preferances. My goal was to create a beer recomendation system so that people don't have to waste time and money trying beer that they don't like, and are more apt to try something new that they will enjoy based on past preferances.  

## Sources
User and rating data from BeerAdvocate.com 
Addtional data for content filtering from brewerydb.com

## Exploratory Data Analysis 
This shows the amount of reviews by beer type of the 10 most popular styles of beer in the dataset: 

![image of 10 most popular individual beer styles in dataset](/readme/OxfordPetData.png)

If we group the styles together into more broad styles we can see just how popular IPAs are:

![image of 10 most popular grouped beers styles in dataset](/readme/OxfordPetData.png)

This shows the most popluar breweries in the dataset:

![image of 10 most popular breweries in dataset](/readme/OxfordPetData.png)

And this show what kinds of beer they are brewing:

![image of 10 most popular breweries with breakdown of styles of beer brewed in dataset](/readme/OxfordPetData.png)

## Data Organization 
After EDA, the data had to be reshaped to be able to work with surprise.  It had to be in a pandas DataFrame with the columns: User ID, Item and Review.

Insert pic here.

## Model Results

![image of model outcomes](/readme/imagenet2_testcm.png)

## Frameworks / Libraries Used:
- Surprise! 
- BeautifulSoup
- Sklearn
- Matplotlib
- Seaborn
- Pandas
- Numpy
- Wordcloud
- Scipy 
- ipywidgets

## Credits
By Lois Rosenbloom 
