# Spotify_Recommendation_System
I have created Music Recommendation System using Spotify Dataset. 
To do this, I presented some of the visualization processes to understand data and done some EDA(Exploratory Data Analysis),
so we can select features that are relevant to create a Recommendation System.

Based on the analysis and visualizations, it’s clear that similar genres tend to have data points that are located close to each other while similar types of songs are also clustered together.
This observation makes perfect sense. Similar genres will sound similar and will come from similar time periods while the same can be said for songs within those genres. We can use this idea to build a recommendation system by taking the data points of the songs a user has listened to and recommending songs corresponding to nearby data points.
Spotipy is a Python client for the Spotify Web API that makes it easy for developers to fetch data and query Spotify’s catalog for songs. You have to install using pip install spotipy
After installing Spotipy, you will need to create an app on the Spotify Developer’s page and save your Client ID and secret key.
