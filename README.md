# Netflix---EDA-and-Visualization

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Netflix's content dataset to understand its catalogue composition and identify patterns across movies and TV shows.

Using Python, Pandas, Matplotlib, and Seaborn, I explored content distribution, genres, countries, ratings, durations, actors, directors, and release trends to uncover meaningful insights and provide data-driven recommendations.

## 🎯 Objectives

- Understand the distribution of Movies and TV Shows on Netflix.
- Identify the most common genres and content-producing countries.
- Analyse content ratings and duration patterns.
- Explore popular actors and directors based on the number of titles.
- Examine trends in content releases over the years.
- Derive actionable recommendations from the analysis.

## 🛠️ Tools & Technologies

- **Python** – Programming and data analysis
- **Pandas & NumPy** – Data manipulation and cleaning
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Google Colab / Jupyter Notebook** – Development environment

## 🔍 Project Workflow

1. **Data Loading & Initial Exploration**
   - Loaded the Netflix dataset containing 8,807 records and 12 columns.
   - Examined data types, dimensions, unique values, missing values, and duplicates.

2. **Data Cleaning & Preprocessing**
   - Unnested multi-value columns such as cast, country, director, and genre.
   - Handled missing values using appropriate imputation approaches.
   - Standardized duration values and created duration categories.
   - Converted date columns into datetime format and extracted month and year.

3. **Exploratory Data Analysis**
   - Analysed content distribution by type, genre, country, and rating.
   - Explored movie durations and TV show seasons.
   - Identified frequently appearing actors and directors.
   - Examined content release trends over time.

4. **Insights & Recommendations**
   - Summarized key findings and proposed content-related recommendations based on the analysis.

## 📊 Key Insights

- **Content Type:** Movies account for approximately 70% of the catalogue, while TV Shows make up around 30%.
- **Popular Genres:** International Movies, Dramas, and Comedies are among the most represented genres.
- **Top Content-Producing Countries:** The United States, India, the United Kingdom, Canada, and France lead in the dataset.
- **Content Ratings:** Mature-audience categories represent a significant portion of the catalogue.
- **Movie Duration:** The 81–100 minute range is the most common movie-duration category.
- **Content Trends:** The number of titles released increased substantially from 2008 to 2019, followed by a decline in the dataset.

## 💡 Recommendations

- Consider expanding content across popular genres such as Drama, Comedy, and International content.
- Give strategic attention to major content-producing markets, particularly the US and India.
- Consider the 81–120 minute range when evaluating movie content opportunities.
- Maintain a balance between mature-audience content and family-friendly programming.
- Explore opportunities involving frequently represented actors and directors.

## 📁 Repository Structure

```text
Netflix-Data-Analysis/
│
├── CASE STUDY - NETFLIX.ipynb
├── netflix_titles.csv
└── README.md
```

## 📚 Key Learnings

Through this project, I strengthened my practical understanding of:

- Exploratory Data Analysis (EDA)
- Data cleaning and missing-value treatment
- Handling multi-valued categorical columns using `explode()`
- Data transformation and feature engineering
- GroupBy operations and aggregation
- Data visualization and insight generation
- Translating analytical findings into business recommendations

---

**Author:** Umar Reyaz

**Email:** umar16257@gmail.com

[LinkedIn](https://www.linkedin.com/in/umar-reyaz-55a164272) | [GitHub](https://github.com/umar16257-design)
