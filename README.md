# Spotify Audio Feature Engineering & Acoustic Recommendation Engine

[![Author](https://img.shields.io/badge/Author-M%20Akshay%20Sharma-indigo?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005)
[![Category](https://img.shields.io/badge/Domain-Audio%20Signal%20ML%20%26%20Music%20Recommendation-blue?style=for-the-badge)](https://github.com/akshaysharma2005/spotify-song-recommendation-system)
[![Repository](https://img.shields.io/badge/GitHub-spotify-song-recommendation-system-emerald?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005/spotify-song-recommendation-system)

Audio engineering and unsupervised machine learning clustering across 42,000+ Spotify tracks based on acoustic telemetry.

---

## 🚀 Interactive Web Dashboard

This repository features an interactive web application with dynamic analytical calculators, live visual playgrounds, and interactive Chart.js visualizations.

- **Local Host Link**: [http://localhost:8080/Spotify-Song-Prediction-and-Recommendation-System/index.html](http://localhost:8080/Spotify-Song-Prediction-and-Recommendation-System/index.html)
- **Standalone Launch**: Open `index.html` in any modern web browser or serve via:
  ```bash
  python3 -m http.server 8080
  ```

---

## 📊 Key Metrics & Highlights

| Metric | Measured Value | Context |
| :--- | :--- | :--- |
| **Tracked Songs** | 42,305 | High-resolution audio telemetry |\n| **Acoustic Features** | 11 Dims | Danceability, Energy, Valence |\n| **Clustering Model** | K-Means (k=8) | Mood & genre partitioning |\n| **Search Latency** | < 5 ms | K-D Tree Nearest Neighbor |

---

## 🛠️ Tech Stack & Methodology

- **Domain**: Audio Signal ML & Music Recommendation
- **Tags & Frameworks**: `Python` `scikit-learn` `K-Means` `Audio Features` `Spotify API`
- **Interactive UI**: HTML5, Tailwind CSS, Chart.js, FontAwesome

---

## 💡 Strategic Insights & Key Findings

- **Loudness War Correlation**: Loudness (dB) and Energy correlate at +0.76, proving modern compression drives intensity.
- **Valence vs Danceability**: Positive musical valence does not strictly dictate danceability; dark trap beats maintain high dance scores.
- **Clustering Efficacy**: K-Means with k=8 optimal clusters successfully separated workout playlists from sleep/study sets.
- **Sub-5ms Nearest Neighbor**: Standardized StandardScaler + KD-Tree allows instantaneous real-time playlist auto-generation.

---

## 💻 How to Run Locally

### 1. View the Web Dashboard
```bash
python3 -m http.server 8080
# Open http://localhost:8080/Spotify-Song-Prediction-and-Recommendation-System/index.html
```

### 2. Run the Analysis Notebook
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
jupyter notebook
```

---

## 👤 Author

**M Akshay Sharma**  
- **GitHub**: [@akshaysharma2005](https://github.com/akshaysharma2005)  
- **Email**: akshaysharma200508@gmail.com
