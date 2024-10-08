# Content-Based Movie Recommendation System

## Overview
This project implements a content-based movie recommendation system that predicts user preferences based on the TMDB 5000 Movie Dataset sourced from Kaggle. The system analyzes movie characteristics to provide personalized suggestions, enhancing user experience on streaming platforms.

## Dataset
The TMDB dataset consists of **5,000 rows** and **20 columns**, including:

- **Genre**
- **Title**
- **Release Date**
- **Keywords**
- **Overview**
- **Movie ID**
- **Production Company**
- **Production Country**

*For more details, refer to the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).*

## Implementation Steps
1. **Import Dataset:** Load the TMDB dataset for processing.
2. **Data Cleaning:**
   - Remove unwanted data and irrelevant columns.
   - Merge useful columns to create a refined dataset.
3. **Display Final Dataset:** Present the cleaned dataset for review.
4. **Vectorization:** Use the Bag of Words technique to convert text data into numerical vectors.
5. **Cosine Similarity Calculation:** Compute cosine distances between vectors to measure similarity between movies.
6. **Recommendation Generation:** Display a list of movies with the least distance, indicating high similarity to the selected movie

## Technologies Used
- **Python**
- **Pandas**
- **Scikit-learn**
- **NumPy**

## Acknowledgments
- TMDB 5000 Movie Dataset from Kaggle.
