# 🎬 Movie Recommendation System

This project implements a **Content-Based Movie Recommendation System** using cosine similarity on movie metadata. Given a movie name, it suggests similar movies based on features like genres, keywords, cast, and more.

---

## 🚀 Features

- Content-based filtering using cosine similarity
- Movie suggestions based on description and cast
- Clean and simple logic in a Jupyter Notebook
- Uses publicly available movie metadata
- Lightweight and fast, ideal for learning or enhancement

---

## 📦 Dataset

Here is the dataset.

📥 [Download Dataset (Rating)](https://github.com/JENITH47/movie_recommendation_system/blob/main/ratings.csv)
📥 [Download Dataset (Movie)](https://github.com/JENITH47/movie_recommendation_system/blob/main/movies.csv)



---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📷 Output Screenshots

<details>
  <summary>Click to expand screenshots</summary>

  <table>
    <tr>
      <td><img src="https://github.com/JENITH47/movie_recommendation_system/blob/main/2025-07-09%20(9).png" width="400"/></td>
      <td><img src="https://github.com/JENITH47/movie_recommendation_system/blob/main/2025-07-09%20(10).png" width="400"/></td>
    </tr>
   
  </table>

</details>

---

## 🎥 Demo

[▶️ Click to Watch Demo](https://github.com/JENITH47/movie_recommendation_system/blob/main/bandicam%202025-07-09%2019-22-37-825.mp4)  
*A short screen recording showing how the recommendations appear in real time.*

---

## 🧠 How It Works

1. Combine important features from both CSVs (`movies.csv`, `credits.csv`)
2. Clean and process textual data (cast, keywords, genres)
3. Convert all important info into a single "tags" column
4. Use **CountVectorizer** to convert text to vectors
5. Apply **Cosine Similarity** to compute similarity scores
6. Recommend top N similar movies based on a given movie

---

## 📁 Files in This Repository

| File Name                | Description                              |
|--------------------------|------------------------------------------|
| `movie_recomadation.ipynb` | Main notebook with complete source code  |
| `screenshots/`           | Folder with output screenshots           |
| `demo.mp4`               | Demo screen recording                    |
| `README.md`              | This file                                |

---

