# Project - Song Genre Classification

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). I first made use of *pandas* and *seaborn* packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors. 

Next, I used the scikit-learn package to predict whether it correctly classifies a song's genre based on features such as danceability, energy, acousticness, tempo, etc. I implemented some of the common algorithms such as PCA, logistic regression, and decision trees.

## About the Datasets
I have used two different datasets (courtesy of Datacamp).

1. **‘echonest-metrics.json’** contains data that has music features of each track such as danceability, energy, acousticness, tempo, etc on a scale from -1 to 1.  

2. **‘fma-rock-vs-hiphop.csv’** contains extensive data about the tracks and their genre classification (rock or hip-hop).

