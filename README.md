# Analysis-Amazon-Movies-and-TV-Shows

# Reasong for Choosing Tableau for Visualization
*	Two CSV files, title.csv, and credit.csv, with roughly 10k and 140k records respectively, are part of the Amazon Prime dataset. When working with larger datasets in such situations, Tableau is frequently chosen over Bokeh. Because of Tableau's strong data management features, users can work more effectively and efficiently with massive datasets. Additionally, it provides a large variety of data connectors, making connecting to various data sources simpler.
* To quickly build new visualizations, Tableau provides a selection of pre-built templates, charts, and graphs. Analyzing a dataset and making fast prototypes can be helpful.
* When dealing with massive datasets like Amazon Prime, it is really challenging to identify patterns and trends in the data without a suitable visualization. With Tableau's customization features, we have the power to effectively communicate the most important data points from the data set.


# Requirement Gathering and project planing using Mural Board

![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/cd003a7e-86c3-449f-8f41-b38c1fb23b66)


# Potential Questions that are answered by analysis and visualization

![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/67d9604e-3054-473a-979a-634f6cb07b38)


# Data Types and interaction with reports

![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/5dec27e2-d5a0-46ab-9cf3-ba93864ff1b0)


# Explanation of the dataset:
### Dataset Chosen: Amazon Prime Movies and TV Shows

The dataset is available on Kaggle.
Kaggle: https://www.kaggle.com/datasets/dgoenrique/amazon-prime-movies-and-tv-shows

This dataset, which details the American movies and TV episodes that are currently accessible on Amazon Prime, was compiled from Just Watch in March 2023. It consists of two CSV files: "titles.csv" and "credits.csv". We have merged the data from these two CSV files and used them in our project.
* title.csv - The "titles.csv" file contains more than 10k titles with 15 columns. These columns include the title ID, name of the title, show type (movie or TV show), a brief description, release year, age certification, runtime (for TV shows, the length of the episode), genres, production countries, number of seasons (if it's a TV show), IMDB ID, IMDB score, IMDB votes, TMDB popularity, and TMDB score.
*	credits.csv - Over 140k credits of actors and directors are included in the "credits.csv" file, which has five columns that include the person ID on Just Watch, the title ID on Just Watch, the actor or director's name, the character name, and the role (either ACTOR or DIRECTOR). 
This dataset offers insights into the different kinds of content that are available on Amazon Prime, including genre and runtime distributions, popular titles, and details on the producers—such as the actors and directors—who worked on the project.

# Pre-processing on the dataset:
###  	Libraries used for preprocessing the data:
* ast - The Python library ast provides a way to parse and manipulate the source code of a Python program.
*	MultiLabelBinarizer - The class is imported from sklearn.preprocessing module and is used to convert a list of labels into a binary matrix representation, and is often used in multi-label classification tasks.
*	pandas - The Python library pandas are used for reading, manipulating, and analyzing data.
*	NumPy - NumPy is used while working with arrays and matrices of numerical data. 




