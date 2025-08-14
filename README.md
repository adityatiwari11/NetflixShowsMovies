# Netflix Content Analysis & Visualization

## 🎬 Project Overview

This project analyzes a comprehensive Netflix dataset containing information on movies and TV shows. The goal is to extract actionable insights into content performance, trends, and key contributors (actors/directors) using SQL. The findings are intended to be visualized in a Tableau dashboard to help stakeholders make data-driven decisions.

## 🛠️ Tools Used

* **SQL**: For data querying, aggregation, and analysis.
* **Tableau**: For creating interactive data visualizations and dashboards.

## 📊 Dataset

The analysis uses two main tables:

* `titles`: Contains details about each movie and show, including scores, release year, genres, runtime, and age certification.
* `credits`: Contains information about the cast and crew, linking actors and directors to specific titles.

## 🔍 SQL Analysis Highlights

The SQL queries were designed to answer key business questions about the Netflix library. The analysis focused on several areas:

### 🏆 Performance Metrics

* Identified the top and bottom 10 movies and shows based on IMDb scores.
* Calculated average IMDb and TMDB scores for movies vs. shows.
* Compared average scores across different production countries and age certifications.

### 🎭 Actor & Director Insights

* Listed the top 20 most frequent actors and directors.
* Identified actors who have starred in multiple highly-rated titles.
* Calculated the average IMDb scores for movies/shows featuring leading actors.

### 📈 Content & Genre Trends

* Determined the most common genres for both movies and shows.
* Analyzed the number of titles released per decade and per year.
* Found the shows with the highest number of seasons.
* Calculated the average runtime for movies and shows.

## ✨ Final Outcome

The insights gathered from these SQL queries serve as the foundation for an interactive **Tableau dashboard**. This dashboard will allow users to visually explore trends, filter data dynamically, and gain a deeper understanding of Netflix's content landscape.
