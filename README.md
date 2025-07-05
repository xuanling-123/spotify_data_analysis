# 🎧 Spotify Music Analysis Project

This project is an exploratory data analysis (EDA) of Spotify music datasets, combining track-level, artist-level, and audio feature-level information. The goal is to uncover trends in popularity, genre characteristics, and the evolution of musical attributes over time.

---

## 📂 Datasets Used

| Dataset         | Description                                                  |
|-----------------|--------------------------------------------------------------|
| `sp_tracks.csv` | Track metadata (title, artists, duration, popularity, etc.)  |
| `sp_features.csv` | Audio features + genres for each track                      |
| `sp_artists.csv` | Artist metadata (name, followers, genres, popularity)        |

These datasets are merged to form a comprehensive view of songs, artists, and musical characteristics.

---

## 🧠 Key Questions Explored

- How has **music popularity** changed over time?
- What **audio features** are associated with popular songs?
- Which **genres** dominate Spotify in terms of popularity and volume?
- Are songs getting **shorter or more energetic** over time?
- What distinguishes **popular vs non-popular** tracks?

---

## 📊 Analyses & Visualizations

### 1. 📅 Temporal Analysis
- Tracks released have increased over the years and sharply post-2010.
<img width="443" alt="image" src="https://github.com/user-attachments/assets/ffca1c24-cf7d-4d46-8504-3a9077a9dc83" />

- Average song duration is decreasing over the years.
<img width="439" alt="image" src="https://github.com/user-attachments/assets/f494f8c5-a71c-4178-8822-d8b8d89dbf4a" />

### 2. 🔥 Popularity Drivers
- Popular songs tend to have higher **energy**, **danceability**, and **loudness**.
- **Acoustic** and **instrumental** tracks are generally less popular.
<img width="404" alt="image" src="https://github.com/user-attachments/assets/7ceee623-b138-44d4-9f00-d6bc25023d83" />

### 3. 🎵 Genre Insights
- Top 5 most popular genres: Dance, Pop, Rap, Hip-Hop, Reggaeton.
- Dance and Pop songs dominate popularity charts.
<img width="296" alt="image" src="https://github.com/user-attachments/assets/1b665812-6d13-4474-9ad7-5bbaec23f3a0" />
- Genre-wise average duration vary significantly.
<img width="284" alt="image" src="https://github.com/user-attachments/assets/fac4edeb-07dc-423c-a070-cee71e1ae393" />

