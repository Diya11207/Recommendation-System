# Recommendation-System
This project focuses on building a Movie and TV Show Recommendation System using the Amazon Prime Movies and TV Shows dataset. The project begins with comprehensive Data Analysis and Exploratory Data Analysis (EDA) to understand the dataset, identify trends, handle missing values, and extract meaningful insights. After preprocessing and feature engineering, a K-Nearest Neighbors (KNN) based recommendation model is developed to suggest similar content based on content characteristics.
The recommendation system helps users discover movies and TV shows similar to their interests, enhancing the content discovery experience on streaming platforms.


# 🎬 Amazon Prime Movies & TV Shows Recommendation System

A content-based recommendation system built using the **Amazon Prime Movies and TV Shows Dataset**. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and a recommendation model using **K-Nearest Neighbors (KNN)**.

## 🚀 Project Overview

This project analyzes Amazon Prime content and recommends similar movies and TV shows based on metadata such as genre, cast, director, and description.

## 📊 Dataset

- Dataset: Amazon Prime Movies and TV Shows
- Features: Title, Type, Director, Cast, Country, Genre, Rating, Description, Release Year, Duration
- 

## 🔍 Exploratory Data Analysis

Performed:

- Data Cleaning
- Missing Value Treatment
- Duplicate Removal
- Content Distribution Analysis
- Genre Analysis
- Release Year Trends
- Country-wise Analysis
- Data Visualization using Matplotlib and Seaborn

## 🤖 Model Development

### Feature Engineering

Combined important features:

- Genre
- Director
- Cast
- Description
- Country

### Vectorization

- TF-IDF Vectorizer

### Recommendation Algorithm

- K-Nearest Neighbors (KNN)
- Cosine Similarity

## 📈 Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA
      ↓
Feature Engineering
      ↓
TF-IDF Vectorization
      ↓
KNN Model
      ↓
Movie Recommendations
```

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## 📂 Project Structure

```text
├── data/
├── notebooks/
├── visuals/
├── model/
├── app.py
├── requirements.txt
└── README.md
```

## 🎯 Results

The KNN model successfully recommends movies and TV shows with similar content based on their metadata, helping users discover relevant titles available on Amazon Prime.

## 🔮 Future Improvements

- Hybrid Recommendation System
- Collaborative Filtering
- Streamlit Deployment
- User-Based Recommendations

## 👩‍💻 Author

**Diya Pathak**

