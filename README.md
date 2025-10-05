# spotify-dataset-analysis
An analysis of global music trends using a Spotify dataset.
#  Unveiling Music Trends: A Spotify Dataset Analysis

This project presents a comprehensive time-series analysis of popular music characteristics using a Spotify track dataset.  
It explores how audio features, production techniques, and listener preferences have evolved across decades and languages, offering valuable insights into the dynamics of popular music.

---

##  Dataset Overview

- **Total Tracks:** 15,828  
- **Attributes:** 22 (including metadata and audio features)  
- **Key Features:**  
  - Acousticness  
  - Danceability  
  - Energy  
  - Instrumentalness  
  - Loudness  
  - Speechiness  
  - Tempo  
  - Valence  
- **Languages:** Tamil, Hindi, English, and others  
- **Goal:** Identify temporal and cultural patterns that define popular music trends.

---

##  Key Analyses

### **1. Data Exploration**
Initial inspection confirmed a diverse dataset with rich metadata and well-populated audio features suitable for time-series and clustering analysis.

### **2. Popularity Segmentation**
Top 25% of tracks (by Spotify’s popularity score) were analyzed separately to focus on mainstream listening trends.

### **3. Feature Distribution**
Explored the statistical distributions of popularity, duration, key, tempo, loudness, and other attributes to understand foundational trends.

### **4. Clustering Popular Songs**
Applied **K-Means clustering** on `acousticness`, `instrumentalness`, and `speechiness` to uncover latent sound profiles:
- **Cluster 0:** Pop/Vocal-Centric  
- **Cluster 1:** Acoustic/Warm  
- **Cluster 2:** Instrumental/Cinematic  

### **5. Cross-Lingual Insights**
Analyzed danceability, energy, and valence across languages, revealing cultural preferences in musical style and mood.

### **6. Time-Series Trends**
Tracked year-over-year evolution in:
- Danceability & Energy  
- Acousticness & Instrumentalness  
- Loudness & Valence  
- Liveness & Song Duration  

---

##  Insights & Findings

- **Danceability and Energy** have steadily increased, reflecting a modern preference for upbeat, rhythm-driven music.  
- **Acousticness** has generally declined, signaling a shift toward more electronic and studio-produced sounds.  
- **Major modes (1.0)** and **4/4 time signatures** dominate popular music, providing rhythmic familiarity.  
- **Cross-language analysis** shows unique emotional and energetic characteristics for each linguistic group.  

---

##  Conclusion

This analysis demonstrates that popular music is an ever-evolving art form influenced by cultural, technological, and emotional forces.  
Data-driven methods reveal not only what songs are popular but **how the sound and emotional design of music itself have changed over time**.

By leveraging audio features and machine learning, researchers and creators can better understand global music patterns and anticipate future directions in the industry.

---

##  Tools & Libraries

- **Python**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**

---

##  How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/ag1476790-arch/spotify-music-trends.git
