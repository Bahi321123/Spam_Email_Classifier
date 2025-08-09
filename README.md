# Spam_Email_Classifier
## ***Spam Email Classifier***

This is a small student project that classifies short messages as ***Spam*** or ***Ham (Not Spam)*** using basic Natural Language Processing and a Naive Bayes classifier. I built it to practice text cleaning, vectorization, and simple ML modeling.

---

## ***Why I made this***
I wanted a quick hands-on project to understand how text data is processed and how a simple classifier can detect spam messages. It was also a good way to practice using Google Colab and publishing a project on GitHub.

---

## ***Features***
- ***Text preprocessing:*** lowercase, remove punctuation, stopwords  
- ***Vectorization:*** Bag-of-Words using **CountVectorizer**  
- ***Model:*** **Multinomial Naive Bayes**  
- ***Interactive demo:*** test your own messages in Google Colab  
- ***Dataset:*** public SMS spam dataset (labels: spam / ham)

---

## ***Technologies***
- ***Python 3.13***  
- ***pandas***  
- ***numpy***  
- ***scikit-learn*** (CountVectorizer, MultinomialNB)  
- ***nltk*** (for stopwords)  
- ***Google Colab*** (recommended)

---

## ***How to run (quick)***
1. Open the notebook in **Google Colab** (recommended).  
2. Run all cells in order — the first cell installs required libraries and downloads the dataset.  
3. After training, use the `predict_spam()` function to test custom messages.

**Or run locally:**
```bash
# Install dependencies
pip install pandas numpy scikit-learn nltk

# Open the notebook
jupyter notebook spam_classifier.ipynb
