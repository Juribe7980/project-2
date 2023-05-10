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

![image](https://user-images.githubusercontent.com/120814725/231634795-29a95724-479e-4b95-b343-44c1fe954026.png)

![image](https://github.com/Juribe7980/project-2/assets/120814725/214463b3-e772-4451-aa2e-78b9b62a16e6)



![image](https://github.com/Juribe7980/project-2/assets/120814725/40cfc6fc-6fdb-4af8-a344-12312aa14815)



The variables in general have a very low correlation with each other and with the target variable.

MODEL PERFORMANCE


I executed 2 models:
Decision Regressor
Random Forest Regressor



and I had these results:

DECISION TREE REGRESSOR
Accurary: .72


RANDOM FOREST REGRESSOR
Accuracy:.82


The two models did it bad in precision, very low precision, but if we see at accuracy and recall, Random Forest performed better.

I am giving importance to recall because is telling me how many of the of the positive cases were predicted correctly over all the positive. This is very important if I am trying to predict who is waging more than 50K a year, I want to predict this value correctly.

After PCA, I got these results:

DECISION TREE RERESSOR With PCA

Accuracy : .69


The model performed better without PCA.

RECOMMENDATION
Despite PCA is a powerful tool for avoiding overfiting, in this case, it didn't add performance to the model. I recomend the Decision tree regressor without the PCA.
