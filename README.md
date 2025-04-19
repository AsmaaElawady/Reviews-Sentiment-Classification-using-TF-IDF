# Reviews-Sentiment-Classification-using-TF-IDF

## 📄 Project Summary

This project focuses on sentiment classification using an Amazon product reviews dataset containing over 17,000 records. Each review is labeled as **Positive**, **Neutral**, or **Negative**.

### Dataset
- File: `amazon_reviews.csv`
- Source: Scraped Amazon product reviews
- Classes: `Positive`, `Neutral`, `Negative`

### 🧠 Objectives
1. **Text Preprocessing**: Tokenize reviews, remove stop words, and apply stemming using NLTK.
2. **Label Encoding**: Convert categorical labels into numeric form.
3. **Data Splitting**: 80% for training and 20% for testing.
4. **Vectorization**: Use TF-IDF from `scikit-learn` to transform the reviews into feature vectors.
5. **Modeling**: Train and evaluate three classifiers — **SVM**, **Logistic Regression**, and **Naïve Bayes**.
6. **Evaluation**: Output classification reports for each model's performance.
7. **Interactive Prediction**: Allow users to input a new review, which is preprocessed and vectorized using the **same TF-IDF vectorizer**, then predicted using the trained model.

