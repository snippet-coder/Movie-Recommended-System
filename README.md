# 🍿 Movie Recommendation System – Streamlit Web App


This repository contains a Movie Recommendation System built using machine learning and deployed with Streamlit. It recommends movies based on a selected title using content-based filtering and displays movie posters fetched from the TMDb API.

📁 Project Structure
Recommendation System.ipynb: Notebook that builds and trains the movie recommendation model using scikit-learn and nltk.

Code to run the streamlit.ipynb: Streamlit app code to deploy the recommendation system as an interactive web app.

.

📊 Required Datasets
To run the project, download the following datasets from Kaggle:

TMDB 5000 Movies Dataset

Download and extract:

tmdb_5000_movies.csv

tmdb_5000_credits.csv

Place both CSV files in the root directory of the project (or update paths in the code accordingly).



💡 Features
Content-based movie recommendations using cosine similarity.

Interactive web interface powered by Streamlit.

Movie poster display using TMDb API.

User can select a movie from a dropdown and get top 5 similar recommendations.

🛠️ Technologies Used
Python

Streamlit

scikit-learn

nltk

pandas

numpy

requests (for TMDb API)

pickle (for model storage)

