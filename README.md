# Movie_Recommendation_System - Content Based

<img width="95%" src="https://user-images.githubusercontent.com/70078572/167343659-b8593b98-8c6d-4f36-b562-151ac022a70a.gif">

## 1. About
  
  Recommender System is a system that seeks to predict or filter preferences according to the user's choices. Recommender systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general.

## 2. Data source 

[TMDB dataset from #kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) 

## 3. Working

  #### It works on CountVectorizer #NLP of tags (overview, genres, keywords, cast & crew). 
  
  #### It uses Cosine similarity metric.

## 4. Web App

  This app is Movie Recommender System contains more then 5 thousand movies data. The system output gives you top five recommended movies based on your selected movie.

  Api: Movies poster is fetched from the MovieDatabase(TMBD) api.

  Webapp framework: Streamlit over flask.

  Deployment is done on Heroku: [WebApp](https://movie-recommender-rohit7594.herokuapp.com/)

