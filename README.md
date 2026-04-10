# 🎵 Music Recommendation System

## 📌 Overview

This project is a **Content-Based Music Recommendation System** that suggests songs based on their audio features such as energy, tempo, danceability, and mood.

It uses **Machine Learning (Cosine Similarity)** to find songs that are similar in terms of musical characteristics.

---

## 🚀 Features

* Recommend songs based on input song name
* Uses audio features like:

  * Danceability
  * Energy
  * Tempo
  * Valence (mood)
* Fast and efficient similarity computation
* Full-stack implementation (Flask + React)

---

## 🧠 How It Works

1. Dataset is cleaned and preprocessed
2. Relevant audio features are selected
3. Features are normalized using StandardScaler
4. Cosine similarity is used to compute similarity between songs
5. Top similar songs are returned as recommendations

---

## 🛠️ Tech Stack

### Backend:

* Python
* Flask
* Scikit-learn
* Pandas

### Frontend:

* React (Vite)
* Axios

---

## 📂 Project Structure

```
music-recommender/
│
├── backend/
│   ├── app.py
│   ├── tracks.csv
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

---

### 🔹 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔗 API Endpoint

```
GET /recommend?song=<song_name>
```

Example:

```
http://127.0.0.1:5000/recommend?song=Shape
```

---

## 📊 Dataset

* Spotify Dataset (1921–2020)
* Contains ~600,000 tracks with audio features

---

## 🚀 Future Improvements

* Hybrid recommendation system
* User-based recommendations
* Mood-based filtering
* Deployment using cloud platforms

---

## 👨‍💻 Author

Ami Krishna
