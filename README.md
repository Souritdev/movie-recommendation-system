# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built with **Python**, **Streamlit**, **Scikit-Learn**, and the **TMDB API**.

The application recommends similar movies using machine learning techniques and displays rich movie information including posters, ratings, release dates, genres, and recommendations.

---

# 🌐 Live Demo

### 🚀 Try the Application

**Live Website:**
https://souritdev-movie-recommendation-system-app-yrirds.streamlit.app

### 📂 Source Code

**GitHub Repository:**
https://github.com/Souritdev/movie-recommendation-system

---

# ✨ Features

## 🏠 Home Page

* Displays trending and popular movies from TMDB
* Responsive movie card layout
* Adjustable grid columns
* Movie posters and ratings
* Dynamic category selection

## 🔍 Smart Movie Search

* Search movies by title
* Instant matching results
* Interactive movie cards
* Fast movie discovery experience

## 🎥 Movie Details

* High-quality movie posters
* Overview and storyline
* Release date information
* TMDB ratings
* Genre information
* Cast and movie metadata

## 🤖 Recommendation Engine

* Content-based filtering
* TF-IDF vectorization
* Cosine similarity scoring
* Personalized movie suggestions
* Similar movie recommendations

---

# 🛠️ Tech Stack

## Frontend

* Streamlit

## Backend

* Python

## Machine Learning

* Scikit-Learn
* TF-IDF Vectorizer
* Cosine Similarity

## Data Processing

* Pandas
* NumPy

## APIs & Data Sources

* TMDB API

---

# 📂 Project Structure

```text
movie-recommendation-system/
│
├── app.py
├── main.py
├── requirements.txt
│
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
│
└── README.md
```

### File Description

| File             | Purpose                                 |
| ---------------- | --------------------------------------- |
| app.py           | Streamlit frontend application          |
| main.py          | Backend logic and recommendation engine |
| df.pkl           | Processed movie dataset                 |
| tfidf.pkl        | Trained TF-IDF vectorizer               |
| tfidf_matrix.pkl | TF-IDF feature matrix                   |
| indices.pkl      | Movie title index mapping               |

---

# 🚀 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/Souritdev/movie-recommendation-system.git
cd movie-recommendation-system
```

## 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### Activate the Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### macOS/Linux

```bash
source .venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 TMDB API Configuration

Create a free account at:

https://www.themoviedb.org/

Generate an API Key and create a `.env` file:

```env
TMDB_API_KEY=your_api_key_here
```

For Streamlit Cloud deployment:

```toml
TMDB_API_KEY = "your_api_key_here"
```

---

# ▶️ Run Locally

Start the Streamlit application:

```bash
streamlit run app.py
```

Application URL:

```text
http://localhost:8501
```

---

# ☁️ Deployment

The project can be deployed on:

* Streamlit Community Cloud
* Render
* Railway
* Azure App Service
* AWS

## Streamlit Community Cloud

### Step 1

Push your project to GitHub.

### Step 2

Open Streamlit Community Cloud.

### Step 3

Create a new application.

### Step 4

Select:

```text
Repository: movie-recommendation-system
Branch: main
Main File: app.py
```

### Step 5

Add Secrets:

```toml
TMDB_API_KEY = "your_api_key_here"
```

### Step 6

Deploy the application.

---

# 📊 Recommendation Workflow

```text
Movie Selected
       │
       ▼
Metadata Processing
       │
       ▼
TF-IDF Feature Extraction
       │
       ▼
Cosine Similarity Calculation
       │
       ▼
Top Similar Movies
       │
       ▼
TMDB Metadata Retrieval
       │
       ▼
Recommendations Displayed
```

---

# 📸 Screenshots

## Home Page

* Trending Movies
* Responsive Grid Layout
* Search Functionality
* Dynamic Categories

## Movie Details

* Movie Poster
* Overview
* Ratings
* Genres
* Recommendations

---

# 🔮 Future Improvements

* User Authentication
* Watchlist Feature
* Personalized Recommendations
* Collaborative Filtering
* Genre-Based Filtering
* Movie Trailers
* Advanced Search
* Favorites System
* User Profiles

---

# 🤝 Contributing

Contributions are welcome.

### Fork Repository

```bash
git fork
```

### Create Branch

```bash
git checkout -b feature/new-feature
```

### Commit Changes

```bash
git commit -m "Add new feature"
```

### Push Changes

```bash
git push origin feature/new-feature
```

### Open Pull Request

Submit your Pull Request for review.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

### Sourit Dev

GitHub:
https://github.com/Souritdev

LinkedIn:
(Add your LinkedIn profile here)

---

## ⭐ Support

If you found this project useful:

* Star the repository
* Share the project
* Give feedback
* Contribute improvements

⭐ Thank you for visiting the project!
