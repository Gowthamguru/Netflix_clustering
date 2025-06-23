# 🎬 Netflix Movies and TV Shows Clustering

This project demonstrates how to apply **unsupervised machine learning** to cluster Netflix movies and TV shows based on various features like **genre**, **rating**, and **duration**. The goal is to discover similar content groups to enable **personalized recommendations** and **insights for content strategy**.

---

## 📌 **Project Objectives**

- Perform **data cleaning & preprocessing** on the Netflix dataset
- Apply **feature engineering** to enrich and transform data
- Use **K-Means**, **Hierarchical Clustering**, and **DBSCAN** to group similar content
- Visualize clusters with **PCA** and **t-SNE**
- Evaluate cluster quality using **Silhouette Score**, **Inertia**, and **Davies-Bouldin Index**

---

## 📂 **Dataset**

- **Source:** Netflix Movies and TV Shows dataset
- **Format:** CSV
- **Size:** ~7,787 entries, 12 columns  
  | Column | Description |
  |--------|--------------|
  | show_id | Unique ID |
  | type | Movie / TV Show |
  | title | Title name |
  | director | Director(s) |
  | cast | Main actors |
  | country | Production country |
  | date_added | Date added to Netflix |
  | release_year | Release year |
  | rating | Age rating (PG, TV-MA, etc.) |
  | duration | Runtime or number of seasons |
  | listed_in | Genre(s) |
  | description | Short synopsis |

---

## ⚙️ **Tech Stack**

- **Language:** Python 3
- **Libraries:** 
  - `pandas`, `numpy` (Data handling)
  - `scikit-learn` (Clustering & metrics)
  - `matplotlib`, `seaborn` (Visualization)

---
## 🚀  **Project Steps**
- Data loading & cleaning
- Feature engineering
- Clustering & evaluation
- Visualization

---
## 📊  **Model Building**
 We implemented the following unsupervised machine learning models:
 - K-Means Clustering
 - Hierarchical Clustering
 - DBSCAN Clustering
---
## 🧾 **Key Metrics**
- Silhouette Score
- Inertia (for K-Means)
- Davies-Bouldin Index

---
## ✅ **Model Evaluation**
- Model K-Means Clustering has a silhouette_score of 0.368, and Davies-Bouldin Index is 0.969
- Hierarchical Clustering Silhouette Score: 0.350, Davies-Bouldin Index is 1.084.
- DBSCAN Clustering Silhouette Score is 0.339 and Davies-Bouldin Index is 1.11
- Among all models, the K-Means Clustering model has the best score . Also, K-Means Clustering  model
 has a silhouette_score of 0.368, which is close to 1 than other models, which means the
 K-Means Clustering model is capable of perfectly clustering items.

---
## 🛠️ **Conclusion**
- The K-Means Clustering model has the best score. Also, the silhouette score for the K-Means Clustering model is 0.368,
 which is close to one compared to other models, indicating that it can cluster Movies and TV shows perfectly based on the content.
 - The K-Means Clustering model is the optimal model and well-trained for clustering TV shows and movies based on the content.
