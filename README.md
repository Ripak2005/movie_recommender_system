# 🎬 Movie Recommender System

**Movie Recommender System** is a content-based recommendation engine that suggests similar movies based on user-selected input. It uses **machine learning techniques** like **TF-IDF** and **cosine similarity** to recommend movies based on genre, cast, director, and other metadata.

---

## 📽️ Live Demo

[Watch Live](https://movie-recommender-system-1g1n.onrender.com/)  
---

## 🚀 Features

- 🔍 Get instant movie recommendations
- 🧠 Built using **content-based filtering** logic
- 📚 Uses **TF-IDF** and **cosine similarity**
- 🧹 Cleaned and preprocessed real-world movie data
- ⚡ Lightweight, fast, and interactive interface
- 📱 Deployed with a simple and clean UI (Streamlit or Flask)

---

## 🧠 How It Works

> We use **movie metadata** (genre, cast, crew, keywords) to compute similarity between movies.

- Combine multiple text fields into a single "tags" field
- Apply **TF-IDF vectorization** to extract weighted word features
- Use **cosine similarity** to compute similarity between movies
- Recommend the top N similar movies based on the selected title

---

## 🛠️ Tech Stack

| Component   | Technology Used                  |
|-------------|----------------------------------|
| Language    | Python 3                         |
| Libraries   | Pandas, NumPy, scikit-learn, NLTK|
| ML Logic    | TF-IDF, Cosine Similarity        |
| Frontend    | Streamlit / Flask                |
| Dataset     | TMDB 5000 Movie Dataset (Kaggle) |
