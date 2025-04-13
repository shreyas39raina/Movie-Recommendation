# Movie-Recommendation
This project is a Movie Recommendation System built using Python and machine learning techniques. It helps users find similar movies based on their preferences by analyzing movie metadata like titles, genres, keywords, cast, and crew. 
# 🎬 Movie Recommendation System

This project is a simple yet effective **Movie Recommendation System** that suggests similar movies based on the one you like. It uses **content-based filtering** and **NLP techniques** to recommend titles by analyzing genres, keywords, cast, and crew.

## 📁 Files Included

- **Movie Recommendation.ipynb** – The Jupyter Notebook with the full implementation.
- **movies.csv** – The dataset containing details of all movies.
- **README.md** – Project documentation.


## 📊 Dataset

The dataset used is `movies.csv`, which contains:

- Movie Title
- Overview
- Genres
- Keywords
- Cast & Crew
- Release Date
- Popularity, etc.

The dataset is a cleaned version of the combined TMDB 5000 movie metadata.

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Scikit-learn** – Cosine similarity, vectorization
- **NLP (Natural Language Processing)** – Text cleaning and vectorization
- **Jupyter Notebook** – Development environment

## 🧠 How It Works

1. Preprocess movie metadata by combining key features like genres, keywords, cast, crew, and overview.
2. Convert combined features to numerical vectors using **CountVectorizer**.
3. Compute similarity scores using **Cosine Similarity**.
4. Based on the input movie, recommend the top 5–10 similar movies.

## 🖥️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/shreyas39raina/movie-recommendation-system.git
   cd movie-recommendation-system
2. Launch Jupyter Notebook:
```bash
jupyter notebook "Movie Recommendation.ipynb"
Run all the cells and enter any movie title from the dataset to get similar movie recommendations!
```
🔍 Example:
If you search for "Avatar", you might get similar movies like:

John Carter

Guardians of the Galaxy

Star Trek Into Darkness

Interstellar

The Avengers

🚀 Features
Recommends movies instantly using pre-computed similarity matrix.

Handles missing data and text cleaning efficiently.

Easy to expand using user ratings or hybrid methods (future enhancement).

🙋 Contact
Shreyas D
www.linkedin.com/in/shreyas-d-9668a422a
📧 shreyasappu952003@gmail.com


