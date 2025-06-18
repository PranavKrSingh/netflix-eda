# 📊 Netflix EDA Project

This project performs **Exploratory Data Analysis (EDA)** on Netflix's content dataset to uncover insights about the types, trends, and distribution of movies and TV shows available on the platform.

## 📁 Dataset

- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File**: `netflix_titles.csv`
- The dataset includes information such as title, director, cast, country, release year, rating, duration, and more.

## 🎯 Objectives

- Understand the distribution of content type (Movie vs TV Show)
- Explore trends over the years
- Analyze ratings distribution
- Visualize movie durations
- Examine content production by country

## 🧰 Technologies Used

- Python 🐍
- Pandas 🐼
- Matplotlib 📈
- Jupyter Notebook 📓

## 📌 Key Steps in the Notebook

1. **Data Cleaning**
   - Handling missing values
   - Filtering relevant columns

2. **Analysis & Visualizations**
   - Bar plot: Number of Movies vs TV Shows
   - Pie chart: Content rating distribution
   - Histogram: Distribution of movie durations
   - Line chart: Year-wise content releases
   - Country-wise content count

3. **Exporting Visuals**
   - Graphs saved as PNG images for easy access

## 📷 Sample Visualizations

- `movies_vs_tvshows.png`
- `content_rating_pie.png`
- `movie_duration_histogram.png`

## 🔍 Insights Gained

- Netflix has more **Movies** than TV Shows
- Content production peaked around **2018-2020**
- Most common rating is **TV-MA**
- The USA is the leading producer of content on Netflix

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/PranavKrSingh/netflix-eda.git
   cd netflix-eda
