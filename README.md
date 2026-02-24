# Spotify-Pulse-2023---Data-driven-Hits

-- PROJECT OVERVIEW --

This project performs an in-depth Exploratory Data Analysis (EDA) on the "Most Streamed Songs on Spotify 2023" dataset. The goal is to uncover the underlying factors—both musical (audio features) and structural (platform reach)—that drive a song to the top of the global charts.

-- PROBLEM DEFNITION --

In a saturated digital music market, total stream counts are often treated as the only metric of success. However, this lacks depth. This project addresses the "unpredictability of success" by investigating:

-  How much a song's musical "vibe" (BPM, Energy, Danceability) influences its reach.

-  The correlation between cross-platform presence (Apple Music, Deezer, Shazam) and total Spotify streams.

-  The impact of strategic release timing on long-term performance.

-- KEY INSIGHTS --
  
-  The Kingmaker: Inclusion in Spotify playlists is the single most dominant predictor of total streams, outperforming any individual musical attribute.

-  The Hit Formula: While "vibe" varies, the majority of top-tier hits cluster between 110–130 BPM with high energy and danceability scores.

-  Platform Synergy: Success is rarely isolated; there is a massive "halo effect" where trending on one platform (like Shazam) significantly boosts reachability        across others.

-  Solo Dominance: Solo tracks and duets consistently maintain higher average stream volumes compared to large multi-artist collaborations.

-- DATASET DETAILS --
  
-  The analysis is based on the Spotify Most Streamed Songs 2023 dataset, containing 952 records with 24 attributes, including:

-  Track Metadata: Name, Artist(s), and Artist Count.

-  Reach Metrics: Playlist and chart presence across Spotify, Apple Music, Deezer, and Shazam.

-  Audio Features: BPM, Key, Mode, and percentage scores for Danceability, Valence, Energy, Acousticness, Instrumentalness, Liveness, and Speechiness.

-- ANALYSIS WORKFLOW --
  
-  Data Cleaning: Handled corrupted numeric values in the streams column, formatted platform metrics, and treated missing values in key and shazam_charts.

-  Univariate Analysis: Explored the distribution of streams, musical modes, and temporal release trends.

-  Bivariate Analysis: Analyzed the relationship between platform reach vs. streams and artist count vs. popularity.

-  Multivariate Analysis: Utilized heatmaps and pivot tables to examine the intersection of audio features, release months, and global success.

-- TECHNOLOGY USED --
  
-  Python (v3.x)

-  Pandas: Data manipulation and cleaning.

-  Matplotlib, Seaborn & Plotly: Statistical data visualization.

-  NumPy: Mathematical operations.

-- CONCLUSION & STRATEGY --

The project concludes that "Reachability" is a holistic ecosystem. For artists and labels to maximize success, the data suggests a strategy of prioritizing playlisting over raw audio perfection, targeting mid-tempo energy clusters, and utilizing January or May release windows to maximize accumulation time.
