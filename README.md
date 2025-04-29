# Music Listening Habits Insights Using Spotify API 

A personal project where I have utilised the Spotify API to deep dive into my Spotify listening history through data visualisations, alongside the development of a playlist recommender that utilise insights I found including correlations between audio features and tracks/artists.

Ideal for anyone curious about their musical journey or looking to discover new tracks based on their own tastes.

**To jump to viewing the insights I generated from my listening metadata (extracted using Spotify's API), head to the Data_Visualization.ipynb Jupyter file. Enjoy!**

## Notebooks:

1. ### Data Extraction and Cleaning Notebook:
- Establishing a connection to the Spotify API
- Extracting the required data using the appropriate API endpoints
- Processing and organizing saved tracks, top tracks, and top artists in Pandas dataframes
- Tidying up and structuring data for further analysis and visualisation
  
2. ### Data Visualization Notebook:
   
**Key Statistics on Listening Habits:**
  - **Top Tracks**: short, medium, and long term.
  - **Top Artists**: short, medium, and long term.

  **Audio Feature Distribution:**
  - Audio features (tempo, danceability, energy, etc.) analysed for saved tracks and      for top tracks.
  - Segmented by time ranges for top tracks: short, medium, and long term.
  
  **Correlation Analysis:**
  - Understanding relationships between various audio features.
  - Delved deep with scatter plots and correlation matrices.
  
  **Genre Distribution:** 
  - Exploring genre distributions of saved tracks,  top tracks, and top artists.

  **Spotlight on Artist Specific Data - Frank Ocean:**
  - Analyzed the distribution of audio features from this top artist.
  - Gained insights into his musical style based on the tracks I've saved
  - Significant acousticness presence in a number of tracks
  - Audio features like valence, danceability, energy, and tempo distributions skew  lower, which makes sense considering his style and catalogue
  
### Key Insights So Far:

- Songs with high acousticness have become more prominent in my short and medium-term listening, reflecting a recent dive into classic rock and neo soul.
- Tracks from recent months have showcased higher energy, valence, danceability, and loudness. This upbeat shift is likely influenced by the summer season mood.
- There's a noticeable correlation between danceability, energy, and loudness with respect to acousticness.
- Speechiness appears higher for more energetic songs, suggesting the presence of rap songs.
- Further analysis is in progress to identify patterns between multiple audio features
- Usage of my Spotify account  on our home system introduces genres from family members like Arab pop, especially noticeable in 'top tracks' and 'top artists'

### Upcoming Visualisations:

- Segmenting top genres based on different timeframes (short, medium, long term).
- More in-depth exploration of potential non-linear relationships between multiple audio features.
- Chronological visualization of saved tracks and albums over time.
- Explore subsets of data for trends currently hidden in the entire dataset.
- Investigate potential relationships by combining audio features, like the ratio of loudness to energy in comparison with valence.

### Coming Soon: Playlist Recommender Notebook:
- Plans to incorporate network graphs to better understand relationships between songs or artists based on shared audio features and listening patterns.
- Interactive plot of my listening/saved tracks/top albums over time
- Implement insights and network graph into a playlist recommender model that recommends  playlists based on mood (e.g. inspiring) or activity (e.g. gym or stroll in the park)
- Benchmarking model/assessing performance by comparing with Spotify API's get_recommendations endpoint
- GPT integration to converse naturally when requesting new playlists

**Stay tuned for more updates and feel free to dive into the notebooks for a detailed walkthrough!**
