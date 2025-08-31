# 📝 NLP Text Classification with Python  

**🎯 SMS Spam Detection & Yelp Review Sentiment Analysis using Machine Learning**  

---

## 📌 Description  

This repository demonstrates practical applications of **Natural Language Processing (NLP)** for text classification using Python. It focuses on two real-world problems:  

1. **SMS Spam Detection** – identifying whether a message is *spam* or *ham* using the **SMSSpamCollection dataset**.  
2. **Yelp Review Sentiment Analysis** – classifying reviews as *positive* or *negative* using the **Yelp reviews dataset**.  

The project covers the **end-to-end NLP workflow**:  

- **Preprocessing** – cleaning text, tokenization, stopword removal, stemming/lemmatization.  
- **Feature Engineering** – Bag-of-Words (BoW) and TF-IDF vectorization.  
- **Exploratory Data Analysis (EDA)** – word frequencies, rating distributions, spam vs ham ratios.  
- **Model Training** – Naive Bayes classifiers (MultinomialNB).  
- **Evaluation** – accuracy, precision, recall, F1-score, and confusion matrices.  

**Results**:  
- SMS Spam Classifier → >95% accuracy in detecting spam.  
- Yelp Review Classifier → strong performance in predicting review polarity.  

This repository highlights how simple machine learning techniques can turn raw text into actionable insights and provides a baseline for more advanced NLP models.  

---

## 📂 Datasets  

- **SMSSpamCollection** → SMS messages labeled *ham* or *spam*.  
- **yelp.csv** → Yelp reviews with text and star ratings.  

Sources:  
- [UCI SMS Spam Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)  
- [Yelp Dataset](https://www.yelp.com/dataset)  

---

## ⚙️ Installation  

Clone this repository and install dependencies:  

```bash
git clone https://github.com/your-username/nlp-text-classification-python.git
cd nlp-text-classification-python
pip install -r requirements.txt
