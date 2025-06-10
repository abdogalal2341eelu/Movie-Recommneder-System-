# 🎥 Movie Recommender System – Collaborative Filtering

## 🤖 Overview
This project implements a collaborative filtering recommender system that suggests movies to users based on historical ratings.  
It uses matrix factorization techniques to uncover latent user and movie features from the MovieLens 100K dataset.

---

## 🧰 Tools & Technologies
- Python 3
- Pandas & NumPy
- [Surprise Library](http://surpriselib.com/) or Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset
- **Source:** [MovieLens 100k Dataset](https://grouplens.org/datasets/movielens/100k/)
- **Contents:**
  - `user_id`: Unique ID for each user
  - `movie_id`: Unique ID for each movie
  - `rating`: Rating score (1 to 5)
  - `timestamp` (optional)
  - Movie metadata (title, genres)

---

## 🧠 Algorithms Used
- Matrix Factorization using **Singular Value Decomposition (SVD)**
- (Optional) User-based & Item-based Collaborative Filtering

---

## 🎯 Evaluation
- **RMSE (Root Mean Squared Error)** on test data
- Top-N personalized movie recommendations per user

---

## ✅ Features
- Loads and merges movie ratings and metadata
- Builds training/test sets for evaluation
- Trains collaborative filtering model
- Recommends top-rated unseen movies per user
- Supports expansion to other recommendation strategies

---

## 📁 Files
- `Movie Ratings.ipynb` – Full implementation notebook
- `u.data`, `u.item` – MovieLens dataset files (or converted to `ratings.csv`, `movies.csv`)
- `README.md` – Project documentation

---

## 🔮 Future Work
- Add content-based filtering (using genres, descriptions)
- Build a web interface (e.g. using Streamlit or Flask)
- Integrate hybrid recommendation techniques
