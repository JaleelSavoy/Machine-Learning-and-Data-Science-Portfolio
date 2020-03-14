# Machine Learning and Data Science Portfolio 
### by Jaleel Walter Henry Savoy
A place to describe and link to some personal, individual projects across various repositories.

[Resume](https://www.dropbox.com/s/0g5inoy4uev4dzg/JaleelWalterHenrySavoyResume2020.pdf?dl=0)

## Machine Learning Engineering
[MoivEvolve: Web App to Recommend Movies](https://movievolve.herokuapp.com/)
  - A simple web application built using Flask on Heroku to provide movie recommendations using model-based, user-based collaborative filtering; the recommender uses hierarchical agglomerative clustering. The data used for the project can be found [here](https://grouplens.org/datasets/movielens/). **NOTE: May take a few seconds to load due to Heroku's free dynos sleeping after 30 minutes of no web traffic** [Link to the repository](https://github.com/JaleelSavoy/movie_recommendations)
  
[Web App to Predict Percent Change in Bike Rentals](https://predicted-capital-bikeshare.herokuapp.com/)
  - A simple web application built using Flask on Heroku to predict percent change in Capital Bikeshare rentals. The model is a 3-layer deep neural network built with TensorFlow and is achieves an R-squared of 72.56%. The data used for the project can be found [here](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset#). **NOTE: May take a few seconds to load due to Heroku's free dynos sleeping after 30 minutes of no web traffic** [Link to the repository](https://github.com/JaleelSavoy/BikeSharePrediction)

## Deep Learning Practice Projects
- [Predicting Dota 2 Match Outcomes](https://github.com/JaleelSavoy/DeepLearningPracticeProjects/blob/master/PredictingDota2MatchOutcomes.ipynb)
  - Trained a deep neural network to learn predict Dota 2 match outcomes using only match details, which includes data on the characters each team chooses, the game mode (All Pick, Captain's Mode, etc.), the lobby type (ranked, tutorial etc.), and server region cluster ID. 

- [Deep Clustering on 2016-2017 Season NBA Player Data](https://github.com/JaleelSavoy/DeepLearningPracticeProjects/blob/master/DeepClusteringNBAPlayers20162017.ipynb)
  - Used a Deep Autoencoder to extract latent features from the data and then performed Kmeans Clustering on those features to identify clusters of players that had similar overall performance levels. The clustering groups, when ranked based on average player-efficiency ratings, can be interpreted as general tiers for that season. For example, cluster group 1, which contained Russel West and James Harden, would be MVP-tier, while cluster group 2, which contained LeBron James and Kevin Durant, would be Elite-Tier.
  
- [Deep Autoencoder on Fashion-MNIST](https://github.com/JaleelSavoy/DeepLearningPracticeProjects/blob/master/DeepAutoencoders_fMNIST.ipynb)
  - A showcase of both a standard autoencoder and a convolutional autoencoder on the Fashion-MNIST data set. The notebook shows a straight forward reconstruction using the autoencoders, as well as a demonstration of the autoencoder's ability to reduce noise in image data.

- [Deep Dish Learner](https://github.com/JaleelSavoy/DeepLearningPracticeProjects/blob/master/DeepDishLearnerAnalysis.ipynb)
  - Transfer learning using ResNet-34 to classify pizza images from two categories, Chicago Deep Dish and New York Style

## Reports from Statistical Learning Class (Stat508 @Penn State)
- [Predicting Direction of Weekly Stock Index Movements](https://github.com/JaleelSavoy/DataReports/blob/master/PredictingStockIndexMovementDirection/Data%20Analysis%20Lesson%208.ipynb)
  - Used weekly S&P 500 stock index data to test evalute and compare the performances of models fitted using Logistic Regression, Linear Discriminant Analysis, Quadratic Discriminant Analysis, and k-Nearest Neighbors Classification. 

- [Predicting the Perception of Wikipedia as a Higher Education Teaching Resource](https://github.com/JaleelSavoy/DataReports/blob/master/WikipediaForHigherEducation/WikipediaForHigherEducationAnalysis.ipynb)
  - Used data collected from a 2012 study on faculty members from two universities in Spain, UOC and UPF, to predict respondents' Wikipedia use behavior based on their demographics, backgrounds, and responses to the survey's other questions.
  
- [Predicting Consumer Purchase Behavior](https://github.com/JaleelSavoy/DataReports/blob/master/PredictingOrangeJuicePurchases/DataAnalysisAssignment9.ipynb)
  - Used data collected on consumer purchasing behavior to predict which orange juice brand a consumer would purchase based on features that included report customer loyalty, location of the purchase, prices, discounts, and more.
