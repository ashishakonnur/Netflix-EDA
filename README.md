## Abstract

The coronavirus pandemic has drastically altered our lives. The general population is advised to maintain a social distance and to stay at home. So, aside from online school and employment, what do they do at home? They require some form of amusement. We have no other options for entertainment but to watch TV, movies, or play indoor activities. According to statistics, the number of individuals watching movies on OTT services such as Netflix has increased since the lockdown. So we collected a dataset with information like movie name, cast, type, and ratings and used data mining techniques to evaluate the pattern and extract relevant information from it.

## About the dataset

There are so many datasets under the topic netflix analysis. From that, we have selected a dataset "Netflix Movies and TV shows" based on the fact that more the rows the more data we can infer. This dataset consists of tv shows and movies available on Netflix as of 2020.This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.
[The Netflix Movies and TV Shows dataset](https://www.kaggle.com/shivamb/netflix-shows)
## Algorithm Used

Naive Bayes Classifiers Algorithm
  - Naive Bayes algorithm is a supervised learning algorithm, which is based on Bayes theorem and used for solving classification problems. It assumes that the occurrence of a certain feature is independent of the occurrence of other features. Each feature individually contributes to identify its output without depending on each other.

K-Nearest Neighbor(KNN) Algorithm
  -K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique. It assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. KNN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems. We're attempting to predict TV show and movie ratings using both classification methods.

## Tools Used

Google Colab
## Inference

Using both the classification algorithms we predicted the ratings of TV show and movies. The accuracy score is calculated for both the algorithms and as you can see based on the k value the accuracy score changes in KNN algorithm and it covered all the records within seconds which we have evaluated using confusion matrix. We also have a procedure to calculate the accurate k value which is a additional step through which we can get the k value for the dataset and calculate its accuracy score.<br>
But in Naive Bayes algorithm, we can predict the exact accuracy score in the first time of execution itself. Comparing the accuracy score from KNN and Naive Bayes, I conclude that the coverage of records in a lesser time with the accuracy score of 64.007 KNN algorithm predicts better than Naive Bayes algorithm for the selected dataset.


International Movies appears to be the most popular genre, but this makes no sense in terms of the genre. As a result, let's take a look at the most common genre pairings with International Movies. We evaluated the most popular genre pairings with International Movies using the Apriori and GSP Algorithms. According to the implementation results, dramas account for 53% of all international films (2437). Comedy films account for 30% of all films, while action and adventure films account for 15%.
The most popular genre of international television shows is drama (40 percent). Nonetheless, romantic and crime dramas are ranked second and third in the TV Shows category, respectively (people choose to watch detective and love dramas on TV).
