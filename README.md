# Data Vizualization Final Project
Visualizing Musical Emotion with Data

Tools & Platforms: Observable, D3.js, JavaScript, Kaggle Spotify Dataset


# Project Overview
This project explores the emotional landscape of popular music from 2000 to 2019 using data visualization as both an analytical and interpretive medium. Drawing from Spotify’s Top Hits dataset, which includes quantitative features such as valence, energy, tempo, and danceability, the goal was to translate these algorithmic metrics into visual forms that reflect the complexity and subjectivity of musical emotion. Rather than simply charting data, this work asks: How can we visualize what music "feels-like" not just what it quantitatively measures?


**Static Visualization:**
- The Emotional Spiral: A radial timeline that visualizes the evolving emotional patterns in Billboard’s top hits from 2000 to 2019.  
  - Valence: mapped to color (from melancholy blue to joyful yellow)  
  - Energy: mapped to radial distance from center  
  - Tempo: used to size the data points  
  - Year: drives spiral progression  
- Visual argument: energy has increased in pop music over time, with emotional clustering around specific cultural moments.
- View Static Visualization: https://observablehq.com/d/db9202e0ec47c03e 

**Interactive Visualization:**
- The Mood Galaxy: A force-directed scatterplot that allows users to explore emotional clusters in music by interacting with valence, energy, tempo, and danceability dimensions.
  - Valence: represented through color  
  - Energy: determines motion/velocity 
  - Tempo: controls star size  
  - User Filters: enable discovery of hidden emotional themes (e.g. sad dance music, high-energy melancholic pop)  
- Explore Interactive Visualization: https://observablehq.com/d/88776977f67c3003

**Key Insights:** 
- The increasing energy of top-charting songs across decades suggests a cultural shift toward more intense auditory experiences.
- A notable high-valence cluster around 2011–2013 aligns with the dominance of upbeat "feel-good" pop.
- Users uncovered surprising combinations (e.g. low-valence, high-danceability tracks) not immediately visible in static formats.
- Visualization design decisions, from spiral structure to galaxy simulation, were not just technical but philosophical explorations of how mood lives in music.


**Dataset:**
- Top Hits Spotify 2000–2019: https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019
- This dataset contains audio statistics of the top 2000 tracks on Spotify from 2000-2019. The data contains about 18 columns each describing the track and it's qualities.
