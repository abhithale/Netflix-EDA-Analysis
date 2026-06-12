# Netflix EDA Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Titles dataset containing approximately 8,800 movies and TV shows. The objective is to uncover content distribution patterns, genre trends, country-wise contributions, content growth trends, and other business insights using Python data analysis and visualization libraries.

---

## Dataset Information

The dataset contains information about Netflix titles, including:

* Show ID
* Type (Movie / TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

Dataset Size: ~8,800 Records

---

## Project Objectives

* Understand Netflix content distribution
* Analyze Movies vs TV Shows
* Identify top content-producing countries
* Explore content ratings and genres
* Study yearly and monthly content growth
* Analyze release year patterns
* Examine movie duration distribution
* Generate business insights through visualizations

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Missing value analysis
* Datetime conversion
* Feature extraction (Year Added, Month Added)
* Genre transformation using split() and explode()
* Handling missing country information
* Duration cleaning for movie analysis

---

## Visualizations Included

### Content Distribution

* Movies vs TV Shows

### Country Analysis

* Top 10 Content Producing Countries

### Rating Analysis

* Content Rating Distribution

### Genre Analysis

* Top Genres on Netflix

### Trend Analysis

* Year-wise Content Addition Trend
* Monthly Content Addition Heatmap

### Release Analysis

* Release Year Distribution
* Movie Duration Distribution

---

## Key Insights

* Movies dominate Netflix's content library.
* The United States contributes the highest number of titles.
* India is the second-largest content contributor.
* International Movies, Dramas, and Comedies are the most popular genres.
* Netflix experienced rapid content growth after 2015.
* Peak content additions occurred between 2019 and 2021.
* June, July, and December show higher content release activity.
* Most Netflix content was released after 2010.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```text
Netflix-EDA-Analysis/
│
├── Netflix_EDA.ipynb
├── netflix_titles.csv
├── report/
│   └── Netflix_EDA_Report.pdf
├── images/
│   └── visualizations
└── README.md
```

---

## Conclusion

This project demonstrates the complete EDA workflow, including data cleaning, feature engineering, visualization, and business insight generation. The analysis highlights Netflix's strong focus on movies, recent content, and international expansion.
