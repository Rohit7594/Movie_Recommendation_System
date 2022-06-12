# Movie_Recommendation_System - Content Based

Recommender System is a system that seeks to predict or filter preferences according to the user's choices. Recommender systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general.

This Movie Recommender System contains more then 5 thousand movies data. The system output gives you top five recommended movies based on your selected movie.

It works on count vectorizer #NLP of tags (overview, genres, keywords, cast & crew). 

Data source: TMDB dataset from #kaggle. 

Metric: Cosine similarity metric is used.

Api: Movies poster is fetched from the MovieDatabase(TMBD) api.

Webapp framework: Streamlit over flask.

The model is deployed on Heroku: 

https://movie-recommender-rohit7594.herokuapp.com/

<img width="90%" src="https://user-images.githubusercontent.com/70078572/167343659-b8593b98-8c6d-4f36-b562-151ac022a70a.gif">
