# 📰 Content-Based News Recommendation System

This project builds a **Content-Based News Recommendation System** that suggests articles based on the textual similarity between user preferences and news content. It uses the https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data, which provides article titles, abstracts, and metadata like categories and subcategories.

---

## 📌 Project Description

The system works by:
- Extracting TF-IDF features from article titles and abstracts
- Allowing users to select preferred topics or articles
- Building a user profile vector based on those preferences
- Computing cosine similarity between the user profile and all articles
- Recommending the most relevant news articles

---

## ⚙️ Setup Instructions

1. **Clone the repository**:
```bash
git clone https://github.com/RodainaMOe/articles_recommendation.git
cd articles_recommendationa
