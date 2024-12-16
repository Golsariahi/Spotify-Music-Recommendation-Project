## Overview  
This project focuses on analyzing historical music trends and developing a personalized music recommendation system for Spotify users. By leveraging a dataset of over 170,000 songs and machine learning techniques, the project aims to improve user engagement, enhance the listening experience, and contribute to revenue growth for Spotify.  

---
## Project Goal 
1. Identify the most popular genres and songs on Spotify by understanding how have their popularity trends changed over time
2. Recommend a particular song or artist, based on the features of the songs and the user listening history

---

## Problem Statement   
1. Alleviate the exhaustion customers face when searching for their preferred music
2. Enhance the user experience, increase engagement, and revenue by providing personalized music recommendations

---

## Dataset  
- **Source:** Spotify Song Dataset  
- **Key Features:**  
  - **Song Data:** Title, artist, album, release date, duration, and audio features (e.g., tempo, loudness, key).  
  - **Genre Data:** Information about genres and sub-genres.  
  - **Artist Data:** Number of songs, average tempo, loudness, and popularity metrics.  

---

## Methodology  

### 1. Data Cleaning  
- Removed duplicates and standardized inconsistent data formats.  
- Addressed missing values to ensure dataset completeness.  

### 2. Exploratory Data Analysis (EDA)  
- Identified key trends in music features over time:  
  - Modern music shows increased **energy** and **loudness** with decreased **acousticness.**  
  - Danceable and positive songs correlate strongly with popularity.  
- Explored correlations between features like valence, danceability, and energy.  

### 3. Machine Learning: K-Means Clustering  
- Grouped songs into clusters based on features like tempo, valence, and loudness.  
- Created distinct clusters to identify patterns in genres and song characteristics.  

### 4. Recommendation System  
- Built a **content-based filtering** recommendation engine using cosine similarity.  
- Focused on the top 50,000 popular songs for optimized performance.  
- Validated recommendations by matching test songs to similar clusters.  

---

## Key Insights  
1. Popular songs today tend to be louder, faster, and less acoustic compared to earlier decades.  
2. Danceable and positive songs are more likely to achieve higher popularity.  
3. Clustering effectively groups songs with similar characteristics, improving personalization.  

---

## Business Recommendations  
1. **Data-Driven Playlists:** Use trends like high energy and danceability to curate popular playlists.  
2. **Improved Discovery:** Enhance Spotify’s recommendation engine with clustering and cosine similarity for more accurate suggestions.  
3. **Targeted Marketing:** Promote high-energy and danceable tracks to younger audiences through social media campaigns.  

---

## Tools and Technologies  
- **Python Libraries:** Pandas, Matplotlib, Scikit-learn, Surprise.  
- **Techniques:** K-Means Clustering, Content-Based Filtering, Trend Analysis.  
- **Visualization Tools:** Matplotlib, Seaborn.  

---

## Conclusion  

Through this analysis, significant trends in the music data over time were uncovered. For instance, acousticness decreased over the decades, while energy and loudness increased, reflecting changes in music production trends and listener preferences.

Using K-Means Clustering, songs were grouped based on audio features such as tempo, energy, and loudness. Visualizations showed distinct clusters where songs with similar characteristics were grouped together, while others stood out with noticeable differences. This highlights how musical tastes vary across different listener profiles, showcasing the diversity in consumer preferences.

The recommendation system, built using cosine similarity and song popularity metrics, effectively personalized content for users. By comparing test and recommended song clusters, the system's ability to deliver relevant and accurate suggestions was demonstrated, ensuring a better user experience.

Ultimately, these insights and tools aim to help Spotify enhance content recommendations, retain users, and increase engagement, which can contribute to higher user satisfaction and revenue growth.

---
