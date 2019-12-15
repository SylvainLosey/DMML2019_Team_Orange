# Team Orange
Data Mining and Machine Learning Course  
Master of Information Systems - HEC Lausanne  
Prof Michalis Vlachos

### Team Members:
* Blanck, Constant
* Oswald, Cyrill
* Tsareva, Svetlana
* Losey, Sylvain

## IMDB Movie reviews - Sentiment analysis
For the semester project we have chosen the topic of sentiment analysis for movie reviews from the movie database IMDb. We want to write a model that predicts if a movie review is positive or negative. In addition, the goal would be to identify the best technique to use for the sentiment analysis of movie reviews and to compare the results obtained from these techniques. In this project we have decided to focus on three main techniques: KNN-neighbours, Decision Trees and Logistic Regression.

### Dataset
We have chosen to use a dataset from Kaggle, which is available [here](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) as it provides a combined database of 50'000 movie reviews from IMDb. The reviews are highly polarized, which should help us to have a more reliable model.

### Project structure
Our project is split in two parts, both in the ```code``` folder:

1. **Data cleaning** in the notebook ```1_data_cleaning.ipynb```
1. **Analysis** in the notebook ```2_analysis.ipynb```

_Note that the notebooks should be run in that order, as dependencies are installed in the data cleaning notebook._

The original dataset as well as the cleaned dataset can be found in the ```data``` folder.

## Web app
As we were quite happy with the accuracy of our best model which exceeded 0.9 and didn't see a way to improve these results apart from complicated Neural Networks, we decided to use our model in a more concrete way. As such, we built a simple web app where one can enter a movie review, and our model will predict wheteter it is positive or negative.

[Link to the wep app.](https://whispering-bastion-28721.herokuapp.com/)

![Predictor](https://i.ibb.co/LJRG8rj/Screen-Shot-2019-12-15-at-22-31-14.png "Predictor")

All the details of the implementation are in a dedicated repository: [link](https://github.com/SylvainLosey/predictor).


### Video presentation
The video presentation can be found on [Youtube](https://nvskdvk)
