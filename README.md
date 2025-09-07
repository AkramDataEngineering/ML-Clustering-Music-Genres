# ML-Clustering-Music-Genres
# 🎵 Clustering Music Genres with Machine Learning  

## 📌 Project Overview  
Clustering music genres is a machine learning task focused on **grouping songs based on audio characteristics** like tempo, loudness, danceability, and energy levels. This project uses clustering techniques to segment music tracks, enabling better personalization for **music recommendation systems**.

---

## 🎯 Problem Statement  
Music preferences vary widely across individuals, making it challenging for streaming platforms to **recommend songs** effectively. By analyzing a dataset of popular Spotify tracks and their audio attributes, this project:  
- Identifies **patterns and similarities** between songs.  
- Groups music into clusters, making recommendations more accurate.  
- Provides insights into the audio characteristics of different genres.  

---

## 🛠 Project Workflow  
1. **Data Exploration & Cleaning**  
   - Dataset: Popular Spotify tracks with attributes like BPM, Loudness, Valence, Acousticness, and Speechiness.  
   - Removed unnecessary columns such as `Index`.  

2. **Feature Engineering**  
   - Selected features most relevant to genre similarity:  
     - `Beats Per Minute (BPM)`  
     - `Loudness (dB)`  
     - `Valence`, `Liveness`, `Acousticness`, `Speechiness`  

3. **Clustering with K-Means**  
   - Normalized features with `MinMaxScaler`.  
   - Applied **K-Means clustering** to segment music tracks into **10 distinct clusters**.  

4. **Visualization**  
   - Used **3D Scatter Plots with Plotly** to visualize clusters based on BPM, Energy, and Danceability.  

---

## 📊 Insights  
- Songs with **similar beats and energy** levels grouped together, regardless of their labeled genre.  
- Acoustic tracks and upbeat tracks formed distinct clusters, providing insights for playlist generation.  
- Helps music platforms improve **user experience** with data-driven recommendations.  

---

## ⚙️ Tech Stack  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Plotly  
- **Algorithm:** K-Means Clustering  
- **Dataset:** Spotify music dataset (2000+ songs)  

---

## 🚀 Deliverables  
✅ Cleaned and preprocessed Spotify dataset  
✅ Music segmentation into **10 clusters**  
✅ Interactive 3D visualizations for exploration  
✅ Data-driven recommendations for music platforms  

---

## 🎼 Business Impact  
This project demonstrates how **machine learning** can transform music streaming:  
- Better user retention with **personalized playlists**  
- Insights into emerging trends in music listening behavior  
- Automation of **genre tagging and categorization**  

---
