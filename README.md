# 🎵 Spotify South India Music Trends & Mood Analysis

> Analyzing 700+ Spotify songs from South India — uncovering mood trends, popular artists, and audio patterns across Telugu, Tamil, Malayalam, Kannada, and Hindi music from 2016 to 2026.

---

## 📌 Project Overview

This is an end-to-end data analytics project focused on South Indian music. The goal is to analyze music trends, mood patterns, genre distribution, artist popularity, and audio features across 5 languages using real Spotify data collected via Exportify.

This project covers the complete data analytics workflow:
**Data Collection → Data Cleaning → SQL Analysis → Visualization**

---

## 🎯 Objectives

- Analyze mood and genre distribution across South Indian music
- Identify the most popular artists and songs by language
- Understand how music trends have evolved from 2016 to 2026
- Compare audio features (energy, danceability, tempo, valence) across moods and languages
- Find patterns between song mood and popularity

---

## 📂 Dataset Details

| Parameter | Details |
|-----------|---------|
| Total Songs | 700+ |
| Languages | Telugu, Tamil, Hindi, Malayalam, Kannada |
| Time Period | 2016 – 2026 |
| Source | Spotify playlists via Exportify |
| Song Types | Movie Songs & Private Albums |

### Columns in Dataset:
| Column | Description |
|--------|-------------|
| Track Name | Name of the song |
| Album Name | Movie or album name |
| Artist Name(s) | Singer(s) |
| Language | Telugu / Tamil / Hindi / Malayalam / Kannada |
| Release Year | Year of release |
| Mood | Happy / Sad / Romantic / Energetic / Calm |
| Genre Category | Soul / Dance / Pop / Blues / Acoustic |
| Duration (mins) | Song length in minutes |
| Stream Category | High / Medium / Low |
| Popularity | Spotify popularity score (0–100) |
| Danceability | How suitable for dancing (0–1) |
| Energy | Intensity and activity level (0–1) |
| Valence | Musical positiveness (0–1) |
| Tempo | Speed in BPM |
| Acousticness | Acoustic quality (0–1) |
| Instrumentalness | Vocal vs instrumental ratio (0–1) |
| Liveness | Live performance feel (0–1) |
| Loudness | Overall loudness in dB |
| Speechiness | Spoken words ratio (0–1) |

---

## 🔍 Key Findings

### 🌐 Language Distribution
- **Telugu** dominates with **186 songs (26%)**
- Tamil follows with **165 songs (23%)**
- Hindi: 151 | Malayalam: 103 | Kannada: 102

### 🎭 Mood Analysis
- **Romantic** is the most common mood — **306 songs (43%)**
- Energetic: 150 | Happy: 135 | Sad: 65 | Calm: 54
- South Indians clearly love romantic melodies!

### 🎬 Song Type
- **Movie songs dominate** — 599 songs (84%)
- Private/Independent albums: 111 songs (16%)

### 🎤 Artist Insights
- **Anirudh Ravichander** leads with most songs across languages
- **DSP** and **Thaman S** dominate Telugu music
- **GV Prakash** is the top Tamil music director
- **Hesham Abdul Wahab** dominates Malayalam music

### 📈 Trends (2016–2026)
- Music energy and danceability have **increased year by year**
- 2024–2026 has the **highest popularity scores**
- Private album culture has grown significantly post-2020

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Exportify** | Extracted Spotify playlist data |
| **Microsoft Excel** | Data cleaning, mood & genre classification |
| **MySQL Workbench** | SQL queries and data analysis |
| **Power BI** | Interactive dashboard (uploading soon) |

---

## 🗄️ SQL Queries Performed

20+ SQL queries were written covering:

- Total songs count and language distribution
- Mood and genre category analysis
- Average popularity by language and mood
- Top 10 most and least popular songs
- Top artists by song count and popularity
- Year-wise trend analysis
- Audio feature comparison across moods
- Stream category distribution
- High energy songs filter
- Mood distribution per language

---

## 📊 Dashboard

> Power BI dashboard uploading soon!

**Planned Pages:**
- **Page 1** — Overview (KPIs, language distribution, mood breakdown, year trend)
- **Page 2** — Mood & Audio Analysis (audio features, genre distribution, popularity by mood)
- **Page 3** — Artist & Trends (top artists, language popularity, year-wise trends)

---

## 📁 Repository Structure

```
Spotify-South-India-Music-Analysis/
│
├── dataset/
│   └── spotify_final.csv          # Cleaned dataset (710 songs)
│
├── sql/
│   └── spotify_queries.sql        # All 20+ SQL analysis queries
│
├── dashboard/
│   └── spotify_dashboard.pbix     # Power BI dashboard (coming soon)
│
└── README.md                      # Project documentation
```

---

## 💡 How to Use

1. Clone this repository
2. Open `spotify_final.csv` in Excel or any tool
3. Import CSV into MySQL and run `spotify_queries.sql`
4. Open `spotify_dashboard.pbix` in Power BI Desktop

---

## 🌟 Insights Summary

```
🎵 710 songs analyzed across 5 languages
🌍 Telugu dominates South Indian Spotify streams
💕 43% of South Indian songs are Romantic mood
⚡ Energetic songs have the highest popularity score
🎬 84% are movie songs — Bollywood and Kollywood rule!
📈 Music energy has steadily increased from 2016 to 2026
🎤 Anirudh Ravichander is the most versatile artist
```

---

## 👩‍💻 About Me

**A Vinitha Sree** - Aspiring Data Analyst


📧 vinithasree04@gmail.com
🔗 [GitHub](https://github.com/Vinithasree04)
💼 [LinkedIn](https://www.linkedin.com/in/vinitha-sree)

---

## 📌 Note

This project is part of my data analytics portfolio. The dataset was collected from public Spotify playlists using Exportify for educational and portfolio purposes only.
