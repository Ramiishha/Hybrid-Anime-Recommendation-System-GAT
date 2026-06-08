# 🎌 Hybrid Anime Recommendation System with Graph Attention Networks (GAT)
Hybrid Anime Recommendation System using Graph Attention Networks (GAT), Collaborative Filtering, Content-Based Filtering and Popularity-Based Recommendation.

## 📌 Overview

This project presents a **Hybrid Anime Recommendation System** that combines multiple recommendation techniques to provide accurate, personalized, and diverse anime suggestions.

Traditional recommendation systems often suffer from:

* Cold Start Problem
* Popularity Bias
* Data Sparsity
* Limited Recommendation Diversity

To overcome these challenges, this project integrates:

* ⭐ Popularity-Based Filtering
* 🤝 Collaborative Filtering
* 📚 Content-Based Filtering (TF-IDF)
* 🧠 Graph Attention Networks (GAT)
* 🔄 MMR (Maximal Marginal Relevance) Re-Ranking

The system leverages anime metadata and user interaction data to generate intelligent recommendations while promoting discovery of hidden gems and long-tail anime.

---

## 🚀 Features

✅ Personalized Anime Recommendations

✅ Graph-Based Deep Learning using GAT

✅ Content Similarity using TF-IDF

✅ Popularity-Based Recommendations for New Users

✅ Diversity Optimization using MMR

✅ Interactive Gradio User Interface

✅ Hybrid Scoring Mechanism

✅ Support for Cold Start Scenarios

---

## 🏗️ System Architecture

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Graph Construction
   │
   ▼
Graph Attention Network (GAT)
   │
   ▼
Hybrid Scoring
   │
   ▼
MMR Re-Ranking
   │
   ▼
Anime Recommendations
```

---

## 📂 Dataset

The dataset contains:

* Anime Titles
* Genres
* Ratings
* Popularity Scores
* User Ratings
* User-Anime Interactions
* Anime Metadata

### Important Attributes

| Attribute  | Description             |
| ---------- | ----------------------- |
| anime_id   | Unique Anime Identifier |
| user_id    | Unique User Identifier  |
| title      | Anime Title             |
| genre      | Anime Genres            |
| score      | Average Rating          |
| popularity | Popularity Rank         |
| scored_by  | Number of Ratings       |
| my_score   | User Rating             |
| type       | Anime Type              |
| source     | Source Material         |
| aired      | Airing Year             |

Dataset Source:

* MyAnimeList
* Kaggle Anime Recommendation Dataset

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* PyTorch
* Torch Geometric
* NetworkX
* Matplotlib
* Seaborn
* Gradio

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handling Missing Values
* Removing Duplicate Records
* Genre Processing
* Label Encoding
* Train-Test Split

### 2. Content-Based Filtering

TF-IDF Vectorization is used to transform anime genres and metadata into numerical vectors.

Similarity between anime titles is computed using:

* Cosine Similarity

### 3. Collaborative Filtering

Collaborative Filtering learns user preferences based on:

* User-Item Interaction Matrix
* User Embeddings
* Anime Embeddings

### 4. Graph Attention Network (GAT)

Users and anime are represented as nodes in a graph.

Edges represent user-anime interactions.

GAT learns:

* Complex Relationships
* User Preferences
* Semantic Similarities
* Neighborhood Importance

### 5. Hybrid Recommendation

Final recommendation score combines:

* Popularity Score
* Collaborative Score
* Content Similarity Score
* GAT Score

### 6. MMR Re-Ranking

MMR improves:

* Diversity
* Novelty
* Long-Tail Exposure
* User Exploration

---

## 📊 Evaluation Metrics

The system is evaluated using:

| Metric    | Purpose                    |
| --------- | -------------------------- |
| Precision | Recommendation Accuracy    |
| Recall    | Relevant Item Retrieval    |
| F1 Score  | Precision-Recall Balance   |
| Hit Rate  | Successful Recommendations |
| MRR       | Ranking Quality            |
| NDCG      | Ranking Relevance          |
| Diversity | Recommendation Variety     |
| Novelty   | Hidden Gem Discovery       |
| Coverage  | Catalog Utilization        |

---

## 📈 Results

The Hybrid GAT-based Recommendation System demonstrated:

* Improved Recommendation Accuracy
* Better Personalization
* Enhanced Diversity
* Reduced Popularity Bias
* Better Handling of Cold Start Problems

Compared to traditional recommendation methods, the hybrid model generated more relevant and context-aware anime recommendations.

---

## 🖥️ User Interface

The project includes an interactive **Gradio Interface** where users can:

* Search Anime
* Get Similar Anime Recommendations
* Explore Different Genres
* Receive Personalized Suggestions

---

## 📁 Project Structure

```text
Anime-Recommendation-System-GAT
│
├── data
│   └── Anime.csv
│
├── notebook
│   └── Anime-recommendation-system.ipynb
│
├── report
│   └── anime_recomendation_system-report.docx
│
├── images
│   ├── architecture.png
│   ├── score_distribution.png
│   ├── popularity_distribution.png
│   └── ui.png
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Anime-Recommendation-System-GAT.git
```

Move into project directory:

```bash
cd Anime-Recommendation-System-GAT
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 🎯 Future Enhancements

* Real-Time User Feedback Integration
* Transformer-Based Recommendation Models
* Reinforcement Learning Approaches
* Cloud Deployment
* Mobile Application Integration
* Scalable Production Pipeline

---

## 👩‍💻 Authors

**Ramisha**
Department of Computer Science
Lakshmibai College, University of Delhi

**Manya Sharma**
Department of Computer Science
Lakshmibai College, University of Delhi

---

## 🙏 Acknowledgements

Special thanks to:

* Mrs. Neha Singla
* Mr. Sudhir Kumar Gupta
* Department of Computer Science
* Lakshmibai College, University of Delhi

for their valuable guidance and support throughout the project.

---

## 📜 License

This project is developed for academic and research purposes.

© 2026 Ramisha & Manya Sharma. All Rights Reserved.
