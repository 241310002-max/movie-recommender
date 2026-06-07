# 🎬 Movie Recommendation System

A content-based recommendation engine that suggests similar movies using NLP and Cosine Similarity.

## 📊 Dataset
- Source: Kaggle — TMDB 5000 Movie Dataset
- 4,800+ movies with genres, cast, crew and keywords

## 🔍 How It Works
- Extracted features: genres, cast, crew, keywords, overview
- Converted text to vectors using CountVectorizer
- Calculated movie similarity using Cosine Similarity
- Returns top 5 most similar movies

## 📈 Sample Results
- The Dark Knight → Batman Begins, The Dark Knight, Batman Returns
- The Avengers → Age of Ultron, Civil War, Iron Man

## 🛠️ Libraries Used
- Pandas, NumPy
- Scikit-learn (CountVectorizer, Cosine Similarity)
- Matplotlib, Seaborn

## 📁 Files
- `movie_recommender.ipynb` — Main Jupyter notebook
- `tmdb_5000_movies.csv` — Movies dataset
- `tmdb_5000_credits.csv` — Credits dataset
