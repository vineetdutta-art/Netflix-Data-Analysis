📊 Netflix Data Analysis: Unveiling Movie Trends & User Preferences
🎯 Project Overview

This project analyzes a Netflix movie dataset to uncover trends, patterns, and user preferences. It involves data cleaning, preprocessing, and visualization to understand movie popularity, genres, and audience engagement.

🧩 Objectives

Explore Netflix’s movie dataset for insights into trends.

Identify the most popular genres and years of movie releases.

Categorize movies based on their vote averages.

Visualize metrics like popularity, genre frequency, and release year trends.

📁 Dataset

Source: mymoviedb.csv
Rows: 9827
Columns:

Column	Description
Release_Date	Original release date of the movie
Title	Name of the movie
Overview	Short description (dropped for analysis)
Popularity	Popularity score
Vote_Count	Number of votes
Vote_Average	Average rating
Original_Language	Movie’s language (dropped for analysis)
Genre	Movie genres
Poster_URL	Poster link (dropped for analysis)
🧹 Data Cleaning & Preparation

Converted Release_Date to datetime and extracted year.

Dropped unnecessary columns (Overview, Original_Language, Poster_Url).

Removed duplicates and handled missing values.

Split multi-genre entries and exploded them for detailed analysis.

Categorized Vote_Average into 4 groups:

popular

average

below_avg

not_popular

🔍 Exploratory Data Analysis (EDA)
Key Insights:

Most Frequent Genre: 🎭 Drama

Highest Rated Movies: Spider-Man: No Way Home

Lowest Popularity: The United States vs. Billie Holiday

Year with Most Movies Released: 2020

Most Common Vote Category: Average

Visualizations:

Genre Distribution (countplot)

Vote Average Distribution (countplot)

Movie Release Year Trend (histplot)

Popularity Comparison

🧠 Tools & Libraries
Tool	Purpose
Python	Core programming language
Pandas	Data cleaning & manipulation
NumPy	Numerical computations
Matplotlib	Data visualization
Seaborn	Advanced plotting & style
📈 Results Summary

Drama dominates Netflix’s catalog as the most frequent genre.

Action & Adventure movies gain higher popularity scores.

The majority of movies fall into the “average” rating category.

Movie production surged around 2020.

🚀 Future Scope

Integrate machine learning models for rating prediction.

Build a recommendation system using collaborative filtering.

Include time-series analysis for release trends.

Create a Power BI or Tableau dashboard for business reporting.

🧾 Author

Vineet Kumar Dutta
