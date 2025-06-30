# 🧠 Fake News Detection using Machine Learning

This project is a personal take on solving the fake news detection problem using natural language processing (NLP) and machine learning. It classifies news articles as **real** or **fake** based on their content.

---

## 📌 About the Project

Fake news is a growing concern with serious social impacts. I built this project to explore how machine learning can help automate the detection of misleading or false information.

The model uses text processing techniques and trains a classifier to differentiate between legitimate and fake news articles.

---

## 🔧 Features

- Clean text preprocessing pipeline
- TF-IDF vectorization for feature extraction
- PassiveAggressiveClassifier for fast online learning
- Easily swappable model architecture
- Streamlit app for interactive news testing

---

## 🧠 Technologies Used

- Python 3
- Pandas / NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebooks

---

## 📊 Model Performance

- Accuracy: **92%**
- Algorithm: **PassiveAggressiveClassifier**
- Feature extraction: **TF-IDF**

---

## ▶️ How to Use

Clone the repo and install the dependencies and to run the app:

```bash
git clone https://github.com/your-username/fake-news-detector.git
cd fake-news-detector
pip install -r requirements.txt

streamlit run app.py
