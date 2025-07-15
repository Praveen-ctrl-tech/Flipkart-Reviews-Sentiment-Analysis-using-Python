# Flipkart Reviews Sentiment Analysis using Python 🛒🧠

This project analyzes customer reviews from Flipkart to determine sentiment (positive or negative) using Natural Language Processing (NLP) and machine learning techniques in Python.

## 🔍 Project Overview

The goal of this project is to:
- Clean and preprocess customer reviews
- Convert text to numerical features using TF-IDF
- Build a sentiment classifier using Decision Tree
- Visualize results like sentiment distribution and word clouds

---

## 📁 Dataset

The dataset contains Flipkart product reviews with the following columns:
- `Product_name` – Name of the product
- `Review` – Customer review text
- `Rating` – Rating given by the customer (1–5)

> 💡 Reviews with ratings >= 4 are considered **positive**, and ratings < 4 are **negative**.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib & Seaborn
- WordCloud

---

## 🔄 Workflow

1. **Preprocessing**
   - Lowercasing
   - Removing stopwords
   - Creating sentiment labels from rating

2. **Feature Extraction**
   - TF-IDF Vectorization (`max_features=5000`)

3. **Modeling**
   - Train-test split (80-20)
   - Decision Tree Classifier

4. **Evaluation**
   - Accuracy score
   - Confusion matrix
   - Word cloud for positive reviews

---

## 📊 Visualizations

- **Sentiment distribution bar chart**
- **Word cloud** of most frequent terms in positive reviews
- **Confusion matrix** for classification performance

---

## 📦 Installation

```bash
git clone https://github.com/your-username/Flipkart-Reviews-Sentiment-Analysis-using-Python.git
cd Flipkart-Reviews-Sentiment-Analysis-using-Python
pip install -r requirements.txt
