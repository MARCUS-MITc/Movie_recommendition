# Movie_recommendition
Movie Recommendation System

The data set that i used in this is from kaggle which is TMDB 5000 Movie Dataset. Im providing the link below.

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

This dataset consists of two csv files. 1 is movies and 2nd one is credits.

credits contains data of cast and crew.

movies contains data related to movies like budget, genres, etc..,.

Removed some of the columns from the Movies which are not useful in this recommendition system.

Then merged both data files into one data file.

Then used CountVectorizer object which is a text processing tool that converts a collection of text documents into a matrix of token counts.

The CountVectorizer object can be used to create a bag-of-words model, which is a simplified representation of the text that captures the frequency of each word in the text. The bag-of-words model can be used for tasks such as text classification and text clustering.

Then found the cosine similarity between the vectors to find how similar they are and recommened the movies based on this.
