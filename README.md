# 🎬 Movie Recommender System by HARSH PRASAD

A content-based Movie Recommender System built using **Machine Learning** and deployed using **Streamlit Cloud**. This application suggests similar movies based on user selection and displays their posters using the TMDB API.

---

## 🚀 Live Demo

https://movierecommender28.streamlit.app/

---

## 📌 Features

* 🎯 Recommends top 5 similar movies based on user selection
* 🖼️ Displays movie posters dynamically
* ⚡ Fast and interactive UI using Streamlit
* 🌐 Deployed on cloud (accessible from anywhere)

---

## 🧠 How It Works

The system uses **content-based filtering**:

1. Movie metadata is processed and transformed into feature vectors
2. Cosine similarity is computed between movies
3. Based on selected movie, top similar movies are retrieved
4. Posters are fetched using TMDB API

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **Scikit-learn**
* **Streamlit**
* **TMDB API**
* **Pickle**

---

## 📂 Project Structure

```
Movie_Recommender/
│
├── main.py                # Streamlit application
├── movie_list.pkl         # Movie metadata
├── similarity.pkl         # Precomputed similarity matrix (hosted externally)
├── requirements.txt       # Dependencies
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/HARSH2815/Movie_Recommendar_Hollywood.git
cd Movie_Recommendar_Hollywood
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the application

```
streamlit run main.py
```

---

## ☁️ Deployment

The application is deployed using **Streamlit Community Cloud**:

* Code is hosted on GitHub
* Dependencies are installed via `requirements.txt`
* Large model file (`similarity.pkl`) is fetched dynamically from Google Drive

---

## ⚠️ Note

* The `similarity.pkl` file is large (~180MB), so it is not stored in the repository
* It is downloaded at runtime from external storage

---

## 📈 Future Improvements

* Add movie ratings and overview
* Implement hybrid recommendation system
* Optimize loading time using caching
* Add user authentication and personalization

---

## 👨‍💻 Author

**Harsh Prasad**
🔗 https://github.com/HARSH2815

---

## ⭐ Acknowledgements

* TMDB API for movie data and posters
* Streamlit for easy deployment

---

## 📌 License

This project is open-source and available for educational purposes.
