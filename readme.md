# 🎬 Netflix Data Analysis (EDA Project)

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the Netflix dataset to uncover insights about content distribution, trends, genres, ratings, countries, directors, and overall platform growth.

The objective is to understand Netflix’s content strategy using data-driven analysis.

---

## 📂 Dataset Information
The dataset includes details of Netflix Movies and TV Shows such as:

- Title
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed Genres

---

## 🧹 Data Cleaning & Preprocessing

The following data preprocessing steps were performed:

- Handled missing values in Director, Cast, Country, Rating, and Duration
- Replaced missing values with appropriate labels (e.g., "Unknown")
- Corrected inconsistencies between Rating and Duration columns
- Converted `date_added` column to datetime format
- Created new features:
  - `year_added`
  - `month_added`
- Processed multi-value columns using `split()` and `explode()`

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

### 🎥 Content Type Distribution
- Comparison of Movies vs TV Shows

### 🌍 Top Countries
- Countries contributing the most Netflix content

### 🎭 Top Genres
- Most frequent genres on Netflix

### ⭐ Ratings Analysis
- Distribution of content ratings (TV-MA, TV-14, etc.)

### 📅 Trend Analysis
- Content added by year
- Content added by month
- Growth of Netflix over time

### 🎬 Directors & Cast Analysis
- Top directors by number of titles
- Most frequently appearing actors

### ⏱️ Duration Analysis
- Movie duration distribution
- TV show seasons distribution

---

## 📊 Visualizations Included

- Bar plots for categorical analysis (Genres, Countries, Ratings)
- Count plots for Movies vs TV Shows distribution
- Line plots for yearly and monthly trends
- Histograms for duration analysis
- Exploded analysis for multi-value fields (Cast, Director, Country)

---

## 📈 Key Insights

- Netflix has more **Movies than TV Shows**
- The **United States, India, and United Kingdom** are top contributors
- **International Movies, Dramas, and Comedies** are the most common genres
- Most content is rated **TV-MA and TV-14**
- Netflix shows strong growth after **2015**
- Most movies fall between **90–120 minutes**
- Most TV shows have **1–2 seasons**
- A small number of directors and actors contribute multiple titles

---

## 🚀 Future Improvements

- Build an interactive dashboard using Tableau or Power BI
- Develop a recommendation system based on genres and ratings
- Perform sentiment analysis on descriptions
- Deploy insights using a web application

---

## 📁 Project Structure

    Netflix-Data-Analysis/
    │
    ├── Netflix_Analysis.ipynb 
    ├── netflix_titles.csv 
    ├── README.md 
    └── images

