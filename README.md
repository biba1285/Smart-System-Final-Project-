# 🎬 Movie Ratings Analysis & Feature Engineering

## 📝 Description
This project performs detailed data analysis and feature engineering on the MovieLens dataset to explore user ratings, popular movies, and genre-based trends. The goal is to understand user behavior, transform movie genres into model-friendly features, and prepare a dataset ready for machine learning applications such as recommendation systems or rating predictions.

## ⚙️ Technologies Used
- **Python**
- **Pandas** – for data cleaning and manipulation  
- **Seaborn & Matplotlib** – for data visualization  
- **Scikit-learn** – for feature scaling (MinMaxScaler)

## 📊 Key Processes
- Merging `movies.csv` and `ratings.csv` to create a unified dataset  
- Analyzing:
  - Most rated movies  
  - Distribution of ratings  
- Filtering for popular movies (10+ ratings)
- Creating a **User-Movie matrix** (collaborative filtering foundation)
- Extracting **movie genres** using one-hot encoding (e.g., Action, Comedy, Drama…)
- Calculating **user statistics**:
  - Average rating  
  - Rating standard deviation  
  - Number of ratings given
- Merging user features with movie features
- Scaling numerical features using **MinMaxScaler**

## 🧪 Final Output
A feature-rich dataset that combines:
- User behavior  
- Movie genres  
- Normalized rating metrics  
Prepared for modeling tasks like rating prediction or recommendation systems.

## 🚀 Ideal For
- Recommendation Systems (collaborative or content-based)  
- Demonstrating data wrangling, merging, feature engineering, and EDA  
- GitHub showcase of real-world datasets and preprocessing pipelines

## 📁 Dataset
- [MovieLens Small Dataset](https://grouplens.org/datasets/movielens/)
