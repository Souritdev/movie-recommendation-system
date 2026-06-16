# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built with **Python**, **Streamlit**, **Scikit-Learn**, and the **TMDB API**.

The application recommends similar movies based on movie metadata and displays rich movie information including posters, ratings, release dates, and recommendations.

---

## ✨ Features

### 🏠 Home Page
- Trending movies from TMDB
- Responsive movie card layout
- Adjustable grid columns
- Movie posters and basic information

### 🔍 Movie Search
- Search movies by title
- Instant matching results
- Interactive movie cards

### 🎥 Movie Details
- Poster and movie overview
- Release date
- TMDB rating
- Genre information
- Recommendation engine

### 🤖 Recommendation Engine
- Content-based filtering
- TF-IDF vectorization
- Cosine similarity scoring
- Similar movie suggestions

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Machine Learning
- Scikit-Learn
- TF-IDF Vectorizer
- Cosine Similarity

### Data Sources
- TMDB API

### Data Processing
- Pandas
- NumPy

---

## 📂 Project Structure

```text
movie-recommendation-system/
│
├── app.py                 # Streamlit application
├── main.py                # Backend logic
├── requirements.txt
│
├── df.pkl                 # Movie dataset
├── tfidf.pkl              # Trained TF-IDF vectorizer
├── tfidf_matrix.pkl       # TF-IDF matrix
├── indices.pkl            # Movie index mapping
│
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Souritdev/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

#### Windows

```bash
.venv\Scripts\activate
```

#### macOS / Linux

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 TMDB API Setup

Create a TMDB account:

https://www.themoviedb.org/

Generate an API key and create a `.env` file:

```env
TMDB_API_KEY=your_api_key_here
```

Or for Streamlit Cloud:

```toml
TMDB_API_KEY = "your_api_key_here"
```

---

## ▶️ Run Locally

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## ☁️ Deployment

This project can be deployed on:

- Streamlit Community Cloud
- Render
- Railway
- Azure App Service
- AWS

### Streamlit Cloud

1. Push the repository to GitHub
2. Create a new Streamlit app
3. Select repository and branch
4. Set:

```text
Main file path: app.py
```

5. Add your TMDB API key in Secrets:

```toml
TMDB_API_KEY = "your_api_key"
```

6. Deploy

---

## 📊 Recommendation Workflow

```text
Movie Selected
       │
       ▼
TF-IDF Feature Extraction
       │
       ▼
Cosine Similarity
       │
       ▼
Top Similar Movies
       │
       ▼
TMDB Metadata Fetch
       │
       ▼
Recommendations Displayed
```

---

## 📸 Screenshots

### Home Page

- Trending movies
- Responsive card layout
- Search functionality

### Movie Details

- Poster
- Overview
- Ratings
- Recommendations

---

## 🔮 Future Improvements

- User authentication
- Collaborative filtering
- Personalized recommendations
- Watchlist support
- Genre-based filtering
- Advanced search
- Movie trailers
- Favorites system

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sourit Dev**

GitHub:
https://github.com/Souritdev

---

⭐ If you found this project useful, consider giving it a star.
