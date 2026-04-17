# Spotify Music Analysis


## 🟢 PROJECT DESCRIPTION: 
The Spotify Music Analysis project is a data-driven exploration of the most-streamed songs on the Spotify platform throughout 2023. This project leverages a comprehensive dataset of nearly 1,000 tracks to examine the relationship between a song’s technical musical attributes—such as tempo (BPM), energy, and danceability—and its commercial performance across global streaming charts (Spotify, Apple Music, Deezer, and Shazam). Through the use of advanced data visualization and Power BI modeling, the project transforms raw streaming figures into actionable insights regarding modern music trends.

## 🟢 PROJECT PURPOSE:
The purpose of this project is to identify the key drivers of global music popularity in the digital era. Specifically, it aims to:

1. Decipher "Hit" Characteristics: Determine if specific audio features (like high danceability or energy) correlate with higher stream counts.

2. Analyze Platform Synergy: Understand how presence in Apple Music or Deezer playlists affects a song’s overall performance on Spotify.

3. Identify Market Leaders: Highlight the artists and tracks that dominated the 2023 landscape (e.g., Taylor Swift and The Weeknd) to study their release patterns.

4. Optimize Release Timing: Examine temporal trends (months and days of the week) to pinpoint the most effective times for music launches based on historical streaming peaks.

## 🟢 PROJECT TECH STACK:
The workflow follows a standard data pipeline:

1. Data Source: Spotify 2023 Dataset.

 - <a href ="https://github.com/priyanshu2003719/Spotify-Dashboard/blob/main/Spotify%20All%20%20Dataset.xlsx"> Spotify Dataset</a>
   
2. ETL Layer: Power Query (Cleaning & Formatting).

3. Modeling Layer: Power BI DAX (Creating KPIs like "Avg Streams" and "Total Tracks").

4.  Presentation Layer: Power BI Dashboard (Charts and Interactive Slicers).

 - <a href ="https://github.com/priyanshu2003719/Spotify-Dashboard/blob/main/spotify.pbit">DASHBOARD</a>

## 🟢 PROJECT DATA SOURCE :
- <a href ="https://docs.google.com/spreadsheets/d/11eiH_HurRXnbymNc4pskPdKhnCtC79Tg/edit?gid=183885892#gid=183885892">DATASET SOURCE</a>

## 🟢 PROJECT FEATURES :
1. Business Problems:
   
a) Feature Correlation: "Does a high 'Danceability' or 'Energy' percentage directly correlate with a higher number of streams, or is song popularity independent of technical audio features?"

-> i)Analysis: The data shows a very weak negative correlation between streams and both Danceability ($-0.10$) and Energy ($-0.02$).
   
   ii)Solution: Song popularity is largely independent of these specific technical audio features. While a certain level of "danceability" is common, having a higher percentage does not guarantee more streams. Success is more likely driven by artist brand, marketing, and playlist placement rather than a specific audio "formula."

b)Platform Synergy: "Are tracks that perform well on Shazam (indicating discovery) more likely to reach the Top 10 on Spotify charts within the same month?"

-> i)Analysis: There is a strong positive correlation ($0.60$) between a track's rank on Shazam charts and its rank on Spotify charts.

  ii)Solution: Yes, tracks performing well on Shazam are highly likely to reach the Spotify Top 10. Shazam serves as an early discovery signal—when users "Shazam" a song in       the real world, it typically translates into Spotify streaming momentum within the same month.

c)Release Optimization: "Data shows high average streams for January releases—is this due to lower competition or a specific consumer behavior at the start of the year?"

-> i)Analysis: January releases have an average of 727 Million streams, which is significantly higher than most months (e.g., February at 353M).

   ii)Solution: This is likely due to lower competition. Fewer "blockbuster" albums are released in January, allowing individual tracks to capture a larger share of listener attention and hold top playlist positions for longer periods.

d)Artist Longevity vs. Viral Hits: "How much of the total stream share is held by 'Legacy' artists (tracks released before 2020) compared to new 'Viral' artists of 2023?"

-> i)Analysis:  Legacy Tracks (Pre-2020): Account for approximately 48.8% of total stream volume (approx. 238 Billion).

   ii)Viral 2023 Tracks: Account for roughly 5.3% of the total volume (approx. 25.8 Billion).

   iii)Solution: While 2023 hits generate massive "hype," the bulk of stream share is held by Legacy artists. This highlights the "long-tail" value of music—older hits continue to generate massive revenue long after their release year.

e)Playlist Impact: "What is the 'conversion rate' between being added to a Spotify playlist and actually appearing on the Apple Music or Deezer global charts?"

-> i)Analysis: There is a moderate correlation ($0.27$) between being in Spotify playlists and appearing on Apple Music charts.

  ii)Solution: Spotify playlisting is a gateway, but not a guarantee. While Spotify dominates in sheer volume, "conversion" to other platforms is selective. High performance on Apple Music or Deezer usually requires a track to first break a threshold of ~2,000+ Spotify playlists to gain enough global momentum.

f)Musical Trends: "Is there a dominant 'Key' (e.g., C# Major) or 'BPM' range that currently defines the top 100 tracks, and should new productions aim for these specifications?"

-> i)Analysis: Dominant Key: C# Major is the most frequent key among the Top 100 most-streamed tracks.

   ii) BPM Range: The average for top hits is 122 BPM, with a "sweet spot" between 100 and 140 BPM.

   iii) Solution: New productions should aim for C# Major or B Major and a tempo around 120 BPM. This range is universally effective for both casual mobile listening and radio/club play, maximizing the song's "reach" across different environments.


2. GOAL:
The goal of the Spotify Music Analysis project is to transform raw streaming data into strategic insights that decode the "formula" for global music success.

By analyzing the top-streamed tracks of 2023, the project aims to:

i)Decode Musical DNA: Identify if specific technical attributes like BPM (120 range), Key (C# Major), and Danceability are consistent drivers of high stream counts.

ii)Bridge the Platform Gap: Quantify how cross-platform presence (Spotify, Apple Music, Deezer, and Shazam) accelerates a song’s growth and total reach.

iii)Optimize Commercial Strategy: Pinpoint the most effective release windows—such as identifying why January and Fridays yield higher average engagement—to maximize a track's market impact.

iv) Differentiate Artist Performance: Compare the steady, long-term revenue of Legacy Tracks (pre-2020) against the high-velocity, short-term peaks of 2023 Viral Hits.

Ultimately, the project serves as a Data-Driven Roadmap for artists and record labels to move from intuitive guessing to informed, strategic decision-making in the digital streaming era.



