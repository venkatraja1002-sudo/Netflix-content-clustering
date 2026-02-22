# Netflix-content-clustering
Unsupervised machine learning project that clusters Netflix movies and TV shows using text and numerical features with model comparison.

# Netflix Movies & TV Shows Clustering

## 📌 Project Overview

This project applies unsupervised machine learning techniques to cluster Netflix movies and TV shows based on textual and numerical features such as genre, cast, description, release year, and duration.

The goal is to group similar content together to help understand patterns, improve recommendations, and analyze content distribution.

---

## 🎯 Problem Statement

Streaming platforms like Netflix contain massive amounts of content. Identifying similar content manually is difficult. This project solves that problem by automatically grouping titles into clusters based on similarity.

---

## 📊 Dataset Information

The dataset contains information about Netflix content including:

* Title
* Director
* Cast
* Country
* Release Year
* Rating
* Duration
* Genre
* Description

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🤖 Machine Learning Algorithms

The following clustering algorithms were implemented and compared:

* KMeans Clustering
* Hierarchical Clustering
* DBSCAN

---

## 🔬 Project Workflow

1. Data Cleaning
2. Handling Missing Values
3. Feature Engineering
4. Text Vectorization (TF-IDF)
5. Feature Scaling
6. Model Training
7. Cluster Evaluation
8. Visualization
9. Interpretation

---

## 📈 Evaluation Metrics

Models were evaluated using:

* Silhouette Score
* Davies–Bouldin Index
* Elbow Method

---

## 🧠 Key Insights

* Content can be grouped into meaningful clusters based on textual and numeric attributes.
* KMeans performed best for this dataset.
* Clustering helps discover hidden content patterns.

---

## ▶️ How to Run the Project

Install dependencies:
pip install -r requirements.txt

Run notebook:
jupyter notebook

---

## 📂 Project Structure

```
Netflix-Clustering-Project/
│
├── notebook.ipynb
├── dataset.csv
├── report.pdf
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Build recommendation system using clusters
* Deploy as web app
* Add deep learning text embeddings
* Automate hyperparameter tuning

---

## 📜 License

This project is for educational purposes and open for learning use.

---

## 👨‍💻 Author

Machine Learning Student Project
