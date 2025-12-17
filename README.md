
<h1 align='center'> <font color='grey'><font size=6>🎥🎬<font color="Purple"><b>ZEE5</font> - Recommendation System (Unsupervised Learning)🎬🎥</b></font> </font></h1>

![ZEE5-1](https://github.com/user-attachments/assets/c0077c29-1836-4c67-915a-8f7401f054b3)


# 🎬 Personalized Movie Recommender System

## 📌 Project Overview
This project focuses on building a **personalized movie recommendation system** using user ratings, demographics, and movie metadata.  
The objective is to analyze user behavior and apply multiple **recommendation techniques** to deliver accurate and relevant movie suggestions.

The dataset used is inspired by the **MovieLens-style format** and includes ratings, user profiles, and movie information.

---

## 🎯 Business Objective
As a **Data Scientist at Zee**, the goal is to:
- Understand user viewing preferences
- Build scalable and accurate recommender systems
- Improve user engagement through personalization
- Compare multiple recommendation algorithms and evaluation metrics

---

## 📂 Dataset Description

The dataset consists of **three main files**:

### 1️⃣ Ratings File (`ratings.dat`)
- **Format:** `UserID::MovieID::Rating::Timestamp`
- Ratings are on a **5-star scale**
- Each user has rated **at least 20 movies**
- Used as the core signal for preference learning

### 2️⃣ Users File (`users.dat`)
- **Format:** `UserID::Gender::Age::Occupation::Zip-code`
- Contains demographic information
- Useful for user segmentation and behavior analysis

### 3️⃣ Movies File (`movies.dat`)
- **Format:** `MovieID::Title::Genres`
- Genres are pipe (`|`) separated (e.g., Action|Drama|Comedy)
- Helps in content-based filtering

---

## 🧠 Recommendation Techniques Implemented

### 🔹 Collaborative Filtering
- User–User similarity
- Item–Item similarity
- Pearson Correlation
- Cosine Similarity

### 🔹 Content-Based Filtering
- Genre-based similarity
- User preference profiling

### 🔹 K-Nearest Neighbors (KNN)
- User-based KNN
- Item-based KNN
- Implemented using cosine similarity

### 🔹 Matrix Factorization
- SVD (Singular Value Decomposition)
- Surprise Library SVD
- CMFREC (Collective Matrix Factorization)

### 🔹 Embedding-Based Similarity
- User embeddings
- User–User similarity
- User–Item similarity

---

## 📊 Evaluation Metrics

The recommender systems are evaluated using:

- **MAPE** (Mean Absolute Percentage Error)
- **RMSE / MSE**
- **NDCG** (Normalized Discounted Cumulative Gain)
- **MRR** (Mean Reciprocal Rank)

These metrics help assess both **rating prediction accuracy** and **ranking quality**.

---

## 🛠️ Tech Stack & Libraries

```python
pandas
numpy
matplotlib
seaborn
scipy
scikit-learn
surprise
cmfrec

