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
  
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/16b81fea-495b-4561-9a57-651c85c47dc3)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/6336aec7-e6d1-4b21-b668-3b682ccc88d1)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/776eee79-d0bb-4106-bce7-7b7964345f53)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/3ab51d1d-eed5-4aa4-a5f1-f0ea2fe7632b)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/43ebfa76-c6ba-49d1-8a5b-4edb9fc000ec)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/44bc5014-7db8-4f61-8dae-c0106eb76ab2)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/647ec632-8d2e-41cd-afc9-d5c18ec7381e)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/eca92264-f7f6-471f-aeeb-9450e5e4eb68)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/f4e98fa5-bc68-4aa6-aebf-3eb226020e85)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/eb3778c1-e47a-4c00-bc8d-c535d3a9e78a)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/4a64dada-7e33-405e-92db-72ac9365ad90)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/bccbc67d-fc02-4ec4-af66-33c71a6cd1c0)
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/bc50e31f-c796-4058-b52d-3bd64fe78bc1)

  # Dashboard
  
  ![image](https://github.com/Alagesan-Sushmitha/Analysis-Amazon-Movies-and-TV-Shows/assets/137837229/aaedae3b-3026-49a6-9fde-0180490191e1)
  
### Explanation of dashboard:
With the advent of the internet and communication revolution, almost every human has a smartphone. This led to several businesses moving online. One such industry is the entertainment industry, which has adopted this mode of delivery extensively. It is evident from the sheer number of OTT (Over the top) platforms that are on the rise. Further the e-commerce giant Amazon has not backed up from the competition by introducing their very own OTT platform Amazon Prime. 
This dashboard is primarily designed to provide useful actionable insights for the end users to extract information regarding the myriad of content available on this platform. The dashboard can provide insights into the Amazon TV and Movies shows that were released since 1913 to 2023. The dashboard is aimed at answering various questions related to the distribution of content across different genres, age certifications, production countries, and release years. It also looks at the top N countries and actors based on various criteria such as content production and IMDB score. Additionally, it provides a comparison of TV shows' popularity with seasons across different factors.
Overall, the dashboard is used for exploratory data analysis and to derive insights from the Amazon TV and Movies shows dataset. The insights generated from the dashboard can be used by content creators, producers, and other stakeholders to make informed decisions about content production, marketing, and distribution.










