# Most Streamed Spotify Songs 2024 - Exploratory Data Analysis

[Most Streamed Spotify Songs 2024 Dataset on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024)

**Authors:** Mani Atwal & Paul Ng  

---

## Project Overview
This project explores the most streamed Spotify songs of 2024, analyzing cross-platform metrics from Spotify, YouTube, TikTok, and other streaming services. The goal is to uncover patterns in track popularity, artist dominance, and engagement trends.

Key objectives:
- Understand distribution patterns of Spotify streams and related metrics.
- Explore correlations between Spotify performance and cross-platform engagement.
- Identify outliers and potential opportunities for promotion.
- Analyze the impact of track titles and explicit content on streaming success.
- Visualize cumulative contributions of top tracks and artists.

---

## Dataset
The dataset contains multi-platform streaming metrics and metadata for top Spotify tracks in 2024.

**Key columns:**
- `Spotify Streams`, `Spotify Popularity`, `Spotify Playlist Count`, `YouTube Views`, `TikTok Views`
- `Artist`, `Track`, `Explicit Track`, `Release Date`

**Data Cleaning Steps:**
- Removed null or irrelevant columns (e.g., TIDAL Popularity)
- Converted numeric columns stored as strings to numeric values
- Handled missing values and formatted dates

---

## Methodology
1. **Initial Exploration**  
   - Examined null values and descriptive statistics.
   - Plotted distributions of Spotify streams, YouTube views, TikTok views, and Spotify popularity.

2. **Correlation Analysis**  
   - Investigated relationships between Spotify streams and playlist counts, YouTube views, and TikTok views.
   - Found that Spotify playlist placements have the strongest correlation with streams.

3. **Outlier Detection**  
   - Identified songs with high YouTube views but low Spotify streams.
   - Suggested potential opportunities for Spotify promotion.

4. **Track Title Analysis**  
   - Examined the most frequent words in track titles.
   - Analyzed the impact of word presence on average Spotify streams.

5. **Dominance Analysis**  
   - Ranked tracks and artists by cumulative Spotify streams.
   - A small subset of tracks and artists account for most streams.

6. **Additional Analysis**  
   - Explored trends by release year and explicit vs non-explicit content.

---

## Key Insights
- **Distribution Patterns:** TikTok views, YouTube views, and Spotify streams are heavily right-skewed.
- **Cross-Platform Correlations:** YouTube views correlate better with Spotify streams than TikTok views; playlist count shows the strongest correlation.
- **Outliers:** Some songs perform well on YouTube but not on Spotify — potential promotion opportunities.
- **Track Titles:** Words like _know, love, one_ are associated with higher average streams; generic words often correlate with lower streams.
- **Artist & Track Dominance:**  
  - Top 14% of tracks account for 50% of Spotify streams.  
  - Top 5% of artists account for 50% of streams.
