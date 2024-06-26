# SC1015 DSAI Project: Movie Recommendation
## Our motivation:
- In today’s digital age, streaming platforms are everywhere and user engagement is key, which leads to a growing necessity for these platforms to differentiate themselves.
- Hence, a strong recommendation system is pivotal in keeping users engaged and could not only retain existing users but can also attract more users by leveraging their individual preferences and interests.
<img width="1512" alt="Screenshot 2024-04-24 at 12 15 47 PM" src="https://github.com/jamietannn/SC1015/assets/148201131/c90efed9-045b-4afb-b989-396f06dd19d1">

## Project Goal:
- This project's objective is to develop a movie recommendation system tailored to individual users, providing personalised movie suggestions based on their past movie preferences to keep them engaged with the platform.

## Data used:
We used the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv) from Kaggle, which consists metadata of about 5000 movies extracted from the movie database. We merged the movies and credits into one dataset, cleaned and processed it for Exploratory Data Analysis and Machine Learning.

## Jupyter Notebooks:
- [Notebook](https://github.com/jamietannn/SC1015/blob/main/1015%20Project.ipynb)

## Slide Deck:
- [Presentation slides](https://docs.google.com/presentation/d/17FGo3eEA0RyDWAkpeTLFurLoZrH1vGtaUkgM0o7YJyY/edit?usp=sharing)

# Overview of Data Science Pipeline:
### 1. Data collection:
- Extracted from kaggle, which extracts from the moveie database
- Merged two datasets together: movies + credit
### 2. Data Cleaning and Preprocessing:
- Remove useless features
- Clean null data
- Extract main features
### 3. EDA & Visualization:
Explored, visualized, and generated insights for the following:
- 'genres': 'primary_genre' & 'secondary_genre'
- 'keywords'
- 'popularity', 'vote_average' & 'vote_count'
### 4. Content Based Filtering:
- TF-IDF Vectorization
- Cosine Similarity
### 5. Clustering with Collaborative Filtering:
- Finding optimum number of clusters: Elbow Curve % Silhouette Method
- Principal Component Analysis
- Clustering with KMeans
- Cosine Similarity
### 6. Key Insights & Recommendations:
Analysis:
- Clustering with collaborative filtering is better as it increases personalisation and reduces computational complexity

Limitations:
- Insufficient test data for user preferences
- Popularity bias

Streaming platforms should:
- Focus on increasing user engagement through a more personalised experience
- Regularly update recommendation models with new data for continuous learning and adaptation

# What we learnt from this project:
### Data collection:
- Extracting and merging data files
### Data cleaning and preprocessing:
- Flattening of data
### EDA & Visualization:
Visualisation of data with large number of data points:
- Catergorial data through Bar plot
- Numerical data: Boxplot
  
Visualisation of multiple variables: Heat map & Boxplot
### Machine Learning:
Machine Learning Model:
- KMeans Clustering

Data Analysis techniques:
- Collaborative filtering
- Principal Component Analysis
- Cosine Similarity
- TF-IDF Vectorization

# Contributions:
Data collection: Raeann, Jamie, Yue Cen

Data cleaning & Preprocessing: Raeann

EDA & Visualization: Jamie and Yue Cen

Content-based filtering: Raeann, Jamie, Yue Cen

KMeans Clustering with Collaborative Filtering: Raeann, Jamie, Yue Cen

Reccomendation System: Raeann, Jamie, Yue Cen

Presentation: Raeann, Jamie, Yue Cen

Slides Deck: Raeann, Jamie, Yue Cen

GitHub ReadMe: Raeann, Jamie, Yue Cen

# References:
- https://www.kaggle.com/code/tanusreedas/simple-recommender-system-step-by-step-explained
- https://www.kaggle.com/code/olyapotemkina/movie-recommendation-system-dbscan
- https://www.geeksforgeeks.org/principal-component-analysis-with-python/amp/
- https://medium.com/@jishnumohan481/movie-recommendation-system-using-cosine-similarity-35f8667b6471#:~:text=Recommendation%20systems%20often%20use%20cosine,of%20similarity%20between%20two%20vectors
