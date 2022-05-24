PROJECT DESCRIPTION

This project makes use of a dataset comprised of songs of two music genres (Hip-Hop and Rock) to train a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). It utilizes pandas and seaborn packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors before doing machine learning. Next, the scikit-learn package is used to predict whether it is possible to correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc.  In this case, this project applies common algorithms such as PCA, logistic regression, decision trees, and so forth.


PROJECT DETAIL


1. Preparing our dataset
2. Pairwise relationships between continuous variables
3. Splitting our data
4. Normalizing the feature data
5. Principal Component Analysis on our scaled data
6. Further visualization of PCA
7. Projecting on to our features
8. Train a decision tree to classify genre
9. Compare our decision tree to a logistic regression
10. Balance our data for greater performance
11. Does balancing our dataset improve model bias?
12. Using cross-validation to evaluate our models