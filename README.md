# 💬 Sentiment Analysis Tool

A machine learning-based web application that analyzes text and predicts whether the sentiment is **positive 😊** or **negative 😠** using Natural Language Processing (NLP).

---

## 👨‍💻 DEVELOPER

**Ahmad Khan**
B.Tech CSE Student | AI & ML Enthusiast
---

## 🚀 Features

* 🔍 Real-time sentiment prediction
* 🧠 NLP preprocessing (cleaning, tokenization, stopword removal)
* 📊 TF-IDF feature extraction
* 🤖 Machine Learning models (Logistic Regression & Naive Bayes)
* 📈 Confidence score with interactive bar chart visualization
* 🌐 User-friendly web interface built with Streamlit

---

## 🛠️ Tech Stack

* **Python**
* **Scikit-learn**
* **NLTK**
* **Pandas / NumPy**
* **Streamlit**

---

## 📂 Dataset

* IMDB Movie Reviews Dataset (2000+ samples used)
* Contains labeled reviews:

  * Positive
  * Negative

---

## ⚙️ How It Works

1. Text input is cleaned using NLP techniques
2. Converted into numerical features using TF-IDF
3. Passed into trained ML model
4. Model predicts sentiment
5. Displays result + confidence graph

---

## ▶️ Run Locally

```bash
# Clone repository
git clone https://github.com/your-username/sentiment-analysis-project.git

# Go to project folder
cd sentiment-analysis-project

# Install dependencies
pip install -r requirements.txt

# Run app
python -m streamlit run app.py
```

---

## 📸 Output Example

* Input: *"This movie is amazing"*
* Output: **Positive 😊 (92%)**
* Graph showing probability distribution

---

## 💼 Use Case

* Product review analysis
* Social media sentiment tracking
* Customer feedback analysis

---

## 📌 Future Improvements

* 🔥 Deploy on Streamlit Cloud
* 📊 Add more advanced models (LSTM, BERT)
* 🌍 Multi-language support
* 📈 Dashboard analytics


---

⭐ If you like this project, give it a star!
