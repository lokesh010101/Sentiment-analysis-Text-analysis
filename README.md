# 🎬 Movie Reviews — Text & Sentiment Analysis

> NLP-powered analysis of movie reviews using Topic Modeling (LDA) and Sentiment Classification (Logistic Regression)

---

## 👤 Author






## 📌 Project Overview

This project applies Natural Language Processing (NLP) techniques to analyze a large corpus of movie reviews. It combines:

- **Topic Modeling** using Latent Dirichlet Allocation (LDA) to discover hidden themes in reviews
- **Sentiment Analysis** using Logistic Regression with TF-IDF to classify reviews as Positive or Negative

---

## 🧠 Techniques Used

| Technique | Purpose |
|---|---|
| TF-IDF Vectorization | Convert text to numerical features |
| Latent Dirichlet Allocation (LDA) | Extract dominant topics from reviews |
| Logistic Regression | Classify sentiment (Positive / Negative) |
| Matplotlib | Visualize topic distributions |

---

## 📂 Project Structure

```
movie-sentiment-analysis/
│
├── movie_sentiment_analysis.ipynb   # Main Jupyter Notebook
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

---

## 🗂️ Topics Discovered (LDA)

The LDA model extracted **7 dominant topics** from the reviews:

| Topic ID | Label |
|---|---|
| 0 | Sci-Fi & War Films |
| 1 | Criticism & Audience Reactions |
| 2 | General Movie Opinions |
| 3 | Filmmaking & Acting Quality |
| 4 | Emotional & Character-Driven Stories |
| 5 | Horror & Thriller Movies |
| 6 | Comedy & Popular Films |

---

## 📊 Results

- ✅ **Sentiment Analysis Accuracy:** `0.89` (89%)
- ✅ **Topic Modeling:** Successfully categorized reviews into 7 meaningful clusters
- ✅ **Prediction Example:**
  - `"This movie was fantastic! I loved it."` → **Positive 😊**
  - `"The worst film I have ever seen."` → **Negative 😠**

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/lokeshchawan/movie-sentiment-analysis.git
cd movie-sentiment-analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open `movie_sentiment_analysis.ipynb` in **Jupyter Notebook** or **Google Colab** and run all cells.

---

## 📦 Requirements

See [`requirements.txt`](requirements.txt) for the full list of dependencies.

---

## 🔮 Future Enhancements

- Replace Logistic Regression with deep learning models (LSTM, BERT) for improved accuracy
- Apply hierarchical topic modeling for finer-grained topic discovery
- Build an interactive web dashboard for real-time sentiment prediction
- Expand dataset to include multilingual reviews

---

## 📜 License

This project is submitted for academic purposes under **Master of Data Analytics**, Pillai College, New Panvel (2025–26).
