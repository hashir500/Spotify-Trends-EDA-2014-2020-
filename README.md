# Spotify Trends EDA (2014–2020)

An exploratory data analysis of 1,700+ Spotify tracks collected between 2014 and 2020 across five search themes — love, sad, rock, night, and remix. This project uncovers patterns in song duration, artist dominance, release trends, and thematic shifts across the years.

---

## Dataset

| Property | Detail |
|---|---|
| Source | Spotify (via query-based collection) |
| Rows | 1,701 tracks |
| Columns | 7 |
| Time Period | 2014 – 2020 |
| Themes | love, sad, rock, night, remix |

**Columns:** `Track_ID`, `Track_Name`, `Duration_Min`, `Artists`, `Release_Date`, `Year`, `Query`

---

## Goals

- Analyze how song duration has changed year over year
- Identify which query themes dominated each year
- Find the most frequently appearing artists
- Detect and handle outliers in song duration
- Extract seasonal release patterns from release dates
- Compare duration distributions across themes

---

## Key Findings

- Song durations have gradually decreased year over year, reflecting the shift toward shorter tracks in the streaming era
- The **sad** theme consistently had the highest number of tracks released per year
- **Twenty One Pilots** was the most dominant artist throughout the dataset
- Sad category tracks tend to be longer in duration on average compared to other themes
- **November** saw the highest number of track releases, suggesting a seasonal end-of-year pattern
- 9 outlier tracks exceeding 10 minutes were removed before analysis

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Project Structure

```
Spotify-Trends-EDA-2014-2020/
│
├── Spotify_Trends_EDA_(2014_2020).ipynb   # main analysis notebook
├── spotify_2014_2020_dataset.csv          # dataset
└── README.md                              # project overview
```

---

## How to Run

1. Clone the repository
   ```
   git clone https://github.com/hashir500/Spotify-Trends-EDA-2014-2020-.git
   ```
2. Upload the dataset to your Google Drive under `MyDrive/Datasets/`
3. Open the notebook in Google Colab
4. Run all cells from top to bottom

---

## Author

**Muhammad Hashir**
[GitHub](https://github.com/hashir500)
