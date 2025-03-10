# Movie Recommendation System
This project is a Movie Recommendation System that helps users find movies based on their preferences. It is built using Python, Pandas, and Tkinter (for GUI) and works with a dataset of the Top 250 Movies.
(This project showcases data filtering, text processing, dictionary-based input handling, and basic GUI development which is made using AI)

# How It Works
There are two ways to provide input:

1. Graphical User Interface (GUI): Users can enter their preferences using a dropdown and text input fields.

2. Dictionary-based Input (Code-based): Users can define their preferences directly in the code using a Python dictionary.

# Recommendation Process
User Input: The user provides their preferences, such as genre, actor, director, writer, keywords, tagline, and even a release year range and rating range.
Filtering & Matching: The program goes through the dataset and finds movies that match the given criteria.
Scoring System: Movies are given scores based on how well they match the input.
Genre Matches: +3 points
Actors, Writers, Directors: +2 points for each match
Tagline, Overview, Keywords: +1 point for each match
Final Recommendation: The program sorts the movies by score and displays the Top 10 Best Matches. If no exact matches are found, it suggests top-rated movies from the chosen genre.

# Features
✔ Two Input Methods (GUI-based and dictionary-based)
✔ User-friendly Interface (Tkinter-based dropdowns & text inputs)
✔ Smart Matching (Ignores case differences & minor variations)
✔ Flexible Filtering (Supports multiple input types like actors, genres, and keywords)
✔ Works on CSV Data (Easy to update with a new dataset)

# Requirement to run this code
1. python
2. Pandas
3. Tkinter (if you want to use the GUI System)

# About the Dataset
The dataset used in this project is top_250_cleaned.csv, which contains 250 of the highest-rated movies. It includes the following columns:

Title: The name of the movie
Year: The release year
Rating: IMDb rating of the movie
Genre: List of genres associated with the movie
Casts: Main actors in the movie
Writers: Writers of the movie
Directors: Directors of the movie
Tagline: The tagline of the movie
Overview: A short description of the movie plot
Keywords: Important keywords related to the movie
Note: The dataset is cleaned to ensure proper formatting, and missing values are handled. also the dataset is a combination of two data set merged to add columns like overview and keywords to get better recommendation
Source: official IMDB Dataset
