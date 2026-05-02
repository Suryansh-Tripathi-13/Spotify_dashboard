#Spotify-dashboard

1- Project Title / Headline:-

* 🎵 Spotify Analytics: Music Streaming Trends Dashboard
* A dynamic, interactive data visualization tool built to explore Spotify streaming data—focusing on track performance, artist insights, audio features, and platform-wide listening patterns.



2- Short Description / Purpose:-
 
  
* The Spotify Analytics Dashboard is a visually engaging and analytical Power BI report designed to help users explore and analyze music streaming trends across thousands of tracks and artists. The dashboard focuses on highlighting key streaming metrics like total streams, average streams per track, playlist placements, and audio characteristics such as danceability, energy, valence, and BPM. This tool is intended for use by music analysts, content strategists, digital marketers, and data enthusiasts who seek to understand listening trends and track performance on Spotify and other platforms.



3- Tech Stack:- 

* The dashboard was built using the following tools and technologies:


* 📊 Power BI Desktop – Main data visualization platform used for report creation.
* 🗂️ Power Query – Data transformation and cleaning layer for reshaping and preparing the Spotify dataset.
* 🧮 DAX (Data Analysis Expressions) – Used for calculated measures, KPI cards, and conditional logic.
* 📅 Data Modeling – Relationships established among tables (Spotify Dataset and Calender) to enable time intelligence and cross-filtering.
* 📁 File Format – .pbit for deployment and use as a dashboard template.



4.  Data Source:-

Source: Kaggle (https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

Data on the most streamed Spotify songs of 2023, including details on track names, artist names, release dates, streaming counts across platforms (Spotify, Apple Music, Deezer, Shazam), playlist placements, chart appearances, and audio features such as BPM, key, mode, danceability, energy, valence, acousticness, instrumentalness, liveness, and speechiness.

* The dataset contains the following key fields:
*  track_name – Name of the song.
*  artist(s)_name – Name of the artist or artists.
*  artist_count – Number of artists featured on the track.
*   ate – Release date of the track.
*  streams – Total number of streams on Spotify.
*  in_spotify_playlists – Number of Spotify playlists the track appears in.
*  in_spotify_charts – Number of times the track appeared in Spotify charts.
*  in_apple_playlists / in_apple_charts – Presence on Apple Music.
*  in_deezer_playlists / in_deezer_charts – Presence on Deezer.
*  in_shazam_charts – Presence on Shazam.
*  bpm – Beats per minute (tempo of the track).
*  key / mode – Musical key and mode (Major/Minor).
*  danceability_% / energy_% / valence_% / acousticness_% / instrumentalness_% / liveness_% / speechiness_% – Audio feature percentages.
*  cover_url – URL of the track's album cover image.

A supplementary Calender table was also created to support time intelligence functions (Year, Quarter, Month, Day of Week).


5.  Features / Highlights:-

*  Business problem
*  Goal of the dashboard
*  Walk through of key visuals (briefly!)
*  Business impact & Insights


1-  Business Problem:-
  
The global music streaming industry generates billions of streams annually, yet artists, music analysts, playlist curators, and digital marketers often lack an intuitive way to compare track performance, understand audio trends, and identify what makes a song go viral on platforms like Spotify. Without a centralized analytical view, it becomes difficult to spot patterns in streaming behavior, track cross-platform reach, or evaluate the role of audio attributes in a song's success.


2-  Goal of the Dashboard:- 
  
The goal of this Spotify Analytics Dashboard is to provide a single, interactive Power BI report that enables users to:
*  Monitor total streams, average streams, and track counts at a glance using KPI cards.
*  Analyze streaming trends over time using a line chart by release date.
*  Identify top-performing tracks using the Top 5 Most Streamed Tracks visual.
*  Understand daily and monthly streaming patterns through bar and table visuals.
*  Filter and drill into data by track name, artist, and date for personalized exploration.
  

3- Walk Through of Key Visuals (briefly!):-
  
*  KPI Cards (Top Row): Display Total Streams, Total Tracks, and Avg Streams for a quick performance summary.
* Streams by Release Date (Line Chart): Shows how streams are distributed across different release dates, revealing peak periods of music activity.
*  Track and Streams by Month (Table): A detailed monthly breakdown showing which tracks performed best in each month.
*  Daily Streams for all Tracks (Clustered Bar Chart): Highlights streaming behavior across different days of the week.
*  Top 5 Most Streamed Tracks (Slicer/Visual): Ranks the five highest-streamed songs for quick identification of blockbuster tracks.
*  Track Detail Card (Multi-row Card): Displays metadata — track name, release date, musical key, and mode — for selected tracks.
*  Slicers: Three interactive filters (Track Name, Artist, Date) allow dynamic slicing of all visuals simultaneously.

  

4-  Business Impact & Insights:-

  
*  Tracks appearing in more Spotify playlists consistently show significantly higher total stream counts, reinforcing the critical role of playlist placement in music marketing strategy.
*  Songs released in mid-year months (May–July) tend to accumulate higher streams, suggesting a summer listening surge that labels and artists can strategically target for new releases.
* The majority of top-streamed tracks are in Major mode with high danceability and energy scores, indicating a clear listener preference for upbeat, feel-good music.
*  Weekend days (Friday–Sunday) show the highest streaming volumes, aligning with global leisure patterns and informing the best days for new track releases.
*  Multi-artist collaborations (higher artist_count) tend to outperform solo tracks in stream counts, highlighting the commercial power of featured artists and collaborative releases.




6- Screenshots/Demos:-


* Show what the dashboard looks like.

Spotify_music_trend_analysis_day_1.png

