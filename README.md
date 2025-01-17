Movie Recommendation System 🎥

This project is a Movie Recommendation System that suggests similar movies based on a selected movie. Using the TMDb (The Movie Database) API for fetching movie posters and metadata, this system combines a machine learning-based similarity model with an interactive interface built with Streamlit.

Features

->Movie Suggestions: Recommends five movies similar to the selected movie.

->Interactive User Interface: Powered by Streamlit for an intuitive and easy-to-use interface.

->Poster Fetching: Integrates with the TMDb API to display movie posters for a better user experience.

How It Works

->Data Preprocessing:

Merges TMDb movie and credits datasets.

Combines relevant metadata (e.g., genres, overview, cast, crew) into a single "tags" column.

Uses text preprocessing and feature extraction to prepare data for similarity calculation.

->Modeling:

Extracts features using CountVectorizer from scikit-learn.

Computes cosine similarity between movie feature vectors to find similar movies.

->Recommendation:

Finds the top 5 most similar movies based on the cosine similarity score.


Fetches movie posters using the TMDb API.

->Requirements

Python 3.7+

Required Libraries:

streamlit

pandas

scikit-learn

requests


Dataset and PKL file attachment:-

https://drive.google.com/drive/folders/1n7-sJZ1WbglmaB1Sgrf5-uwxNev6YnhI
