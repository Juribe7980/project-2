Wines from Spain raiting

by Jessica Uribe

Source: https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset****



Context 
This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression tasks. The classes are ordered and not balanced (i.e. the quality goes from almost 5 to 4 points). The task is to predict either the quality of wine or the prices using the given data.

Content The dataset contains 7500 different types of red wines from Spain with 11 features that describe their price, rating, and even some flavor description. The was collected by me using web scraping from different sources (from wine specialized pages to supermarkets). Please acknowledge the hard work to obtain and create this dataset, you can upvote it if you find it useful to use on your projects :)

If the dataset becomes popular I will probably try to create a bigger version with wines from other countries and a wider spectrum of ratings.

Attribute Information

winery: Winery name

wine: Name of the wine

year: Year in which the grapes were harvested

rating: Average rating given to the wine by the users [from 1-5]

num_reviews: Number of users that reviewed the wine

country: Country of origin [Spain]

region: Region of the wine

price: Price in euros [€]

type: Wine variety

body: Body score, defined as the richness and weight of the wine in your mouth [from 1-5]

acidity: Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]

![image](https://github.com/Juribe7980/project-2/assets/120814725/623265d6-93cf-481e-a525-9dc7912cb11b)




Correlation shows degree of linear relationship between variables.It varies 1 from price and ratings have the highest ratings of 42% meaning that they are fairly positive correlated thus when ratings increase, price increase with approximately 50% of the initial increase in ratings. num-reviews and acidity have the lowest positive correlation of 4.4% meaning that number of reviews are lowly affected by the acidity of the wine thus low correlation.

![image](https://github.com/Juribe7980/project-2/assets/120814725/214463b3-e772-4451-aa2e-78b9b62a16e6)



This visualization shows the wine production per year and the acidity and body.
Showing 2017 and 2018 the highest years where the wine's body was considerably higher than the rest of the years.


![image](https://github.com/Juribe7980/project-2/assets/120814725/40cfc6fc-6fdb-4af8-a344-12312aa14815)




This visualization shows the rating of the wines through the years of 2011 to 2018 in relation to their price.
The wine produce in 2011 is the most costly, over 2500 euros, the next was 2014 where a wine was over 1500 euros.


