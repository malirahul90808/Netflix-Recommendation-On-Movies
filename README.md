# 🎬 Netflix Movie Recommendation System

This project is a **content-based movie recommendation system** that suggests movies similar to a user's selected title.  
It uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to find similarities between movie descriptions.

---

## 🚀 Features
- Suggests similar movies based on the input movie title  
- Uses **TF-IDF Vectorization** and **Cosine Similarity** for recommendation  
- Trained on a dataset of **4803 movies**  
- Implemented in **Python** using popular ML libraries  

---

## 🧠 Technologies Used
- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **NLP (TF-IDF Vectorizer, Cosine Similarity)**
- **Jupyter Notebook**

---

## 📊 Dataset
The dataset contains movie metadata such as:
- Movie title  
- Genres  
- Overview (description)  
- Keywords  
- Cast and crew  

*(You can use the “TMDB 5000 Movie Dataset” from Kaggle.)*

---

## ⚙️ How It Works
1. The dataset is cleaned and preprocessed (missing values, text normalization).  
2. Features are extracted using **TF-IDF Vectorization**.  
3. **Cosine similarity** measures how close movies are in feature space.  
4. When a user inputs a movie title, the model returns top 5–10 similar movies.

---

## 💻 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/rahulmali90808/Netflix-Recommendation-System.git
   cd Netflix-Recommendation-System
