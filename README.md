# 🦠 COVID-19 Tweet Sentiment Analysis  

This project applies **Natural Language Processing (NLP)** and **Machine Learning** to analyze public sentiment during the COVID-19 pandemic. Tweets are preprocessed, vectorized, and classified into sentiment categories such as *Positive, Negative, Neutral,* etc.  

---

## 📊 Workflow  

1. **Data Preparation**
   - Datasets: `Corona_NLP_train.csv` & `Corona_NLP_test.csv`
   - New feature created: `Tweet_texts` (concatenation of *Location + Date + OriginalTweet*)
   - Data cleaning: removed dates, hyperlinks, stopwords, special characters using **Regex, spaCy, and NLTK**  

2. **Feature Engineering**
   - Tokenization & Lemmatization  
   - Text vectorization using **TF-IDF** and **CountVectorizer**  

3. **Modeling**
   - Supervised ML models trained:
     - Random Forest Classifier  
     - Logistic Regression  
     - Naïve Bayes  
   - Evaluation using **Accuracy, Precision, Recall, and F1-score**  

4. **Results**
   - Best model: **Random Forest**  
   - Insights into how people expressed **fear, positivity, and uncertainty** during COVID-19.  

---

## ⚙️ Tech Stack  

- **Python 3.9+**  
- **pandas, numpy** – data handling  
- **nltk, spacy, regex** – text preprocessing  
- **scikit-learn** – ML models and evaluation  
- **matplotlib, seaborn** – visualizations  

---

## 📈 Result  

*"Tweet: 'I can’t wait for lockdown to end.' → Classified as **Positive Sentiment***  




