# 📰 Fake News Prediction using Machine Learning

This project predicts whether a news article is **real or fake** using Natural Language Processing (NLP) and machine learning.

---

## 📊 Dataset

- Used dataset: Fake and Real News dataset (Kaggle)
- Contains article titles and text labeled as **REAL** or **FAKE**.
- File path in the notebook: `Datasets/fake_news.csv`
- If you want to try it yourself, download the dataset from:
  👉 [Fake News Dataset on Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **NLTK / Text preprocessing**
- **TfidfVectorizer**
- **Logistic Regression**
- **Jupyter Notebook**

---

## 🧩 Project Workflow

1. **Data Loading & Cleaning**  
   Handle missing values, drop duplicates, and merge datasets if required.

2. **Text Preprocessing**  
   Tokenization, stopword removal, stemming, and vectorization using TF-IDF.

3. **Model Training**  
   Trained Logistic Regression (and optionally Naive Bayes or SVM).

4. **Evaluation**  
   Checked accuracy, precision, recall, and F1-score.

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/fake-news-prediction.git
   cd fake-news-prediction
2. Install dependencies
  Copy code
  pip install -r requirements.txt
3. Run the notebook
  Copy code
  jupyter notebook "02 Fake News Prediction [Supervised].ipynb"
