# Project - Song Genre Classification

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). I first made use of *pandas* and *seaborn* packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors. 

Next, I used the scikit-learn package to predict whether it correctly classifies a song's genre based on features such as danceability, energy, acousticness, tempo, etc. I implemented some of the common algorithms such as PCA, logistic regression, and decision trees.

## About the Datasets
I have used two different datasets (courtesy of Datacamp).

1. **‘echonest-metrics.json’** contains data that has music features of each track such as danceability, energy, acousticness, tempo, etc on a scale from -1 to 1.  

2. **‘fma-rock-vs-hiphop.csv’** contains extensive data about the tracks and their genre classification (rock or hip-hop).

## Key Findings

**Business Question that I try to answer: "Predicting ?"**

These are some of the key findings for this project:
1. The features .

2. The probable features in a typical credit card application are **Gender**, **Age**, **Debt**, **Married**, **BankCustomer**, **EducationLevel**, **Ethnicity**, **YearsEmployed**, **PriorDefault**, **Employed**, **CreditScore**, **DriversLicense**, **Citizen**, **ZipCode**, **Income** and finally the **ApprovalStatus**.

3. Features like **DriversLicense** and **ZipCode** are not as important as the other features in the dataset for predicting credit card approvals, so they are dropped to obtain a more streamlined training.
 
4. Our numeric and non-numeric data (specifically data that are of **float64**, **int64**, and **object** types). Specifically, the features **2, 7, 10** and **14** contain numeric values (of types **float64, float64, int64** and **int64** respectively) and **all the other features** contain **non-numeric values**.

5. The
