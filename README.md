# Fake News Detection using Machine Learning

## 📌 Project Overview

Fake News Detection is a machine learning project that classifies news articles as **real** or **fake** using Natural Language Processing (NLP).
The model analyzes the text of a news headline or article and predicts whether the information is trustworthy.

This project demonstrates how machine learning and text processing techniques can be used to identify misinformation.

---

## 🎯 Objectives

* Detect fake news using machine learning
* Apply Natural Language Processing (NLP) techniques
* Convert text data into numerical form using TF-IDF
* Train a classification model to predict news authenticity

---

## 🧰 Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Logistic Regression

---

## 📂 Project Structure

```
fake-news-detection
│
├── fake_news.py
├── news.csv
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The dataset contains two columns:

| Column | Description                  |
| ------ | ---------------------------- |
| text   | News headline or article     |
| label  | 0 = Real News, 1 = Fake News |

Example:

```
text,label
Government launches new scheme,0
Aliens landed in New York,1
Prime minister announces policy,0
Miracle cure discovered,1
```

---

## ⚙️ Installation

Install required libraries:

```
pip install pandas scikit-learn
```

---

## ▶️ How to Run the Project

Run the Python script:

```
python fake_news.py
```

Enter a news headline when prompted and the model will predict whether it is **Real** or **Fake**.

Example:

```
Enter news: Scientists discover water on Mars
Output: Real News
```

---

## 🧠 Machine Learning Workflow

1. Load dataset using Pandas
2. Convert text into numerical features using TF-IDF
3. Split dataset into training and testing data
4. Train Logistic Regression model
5. Predict whether news is real or fake

---

## 📈 Future Improvements

* Use larger datasets
* Add Deep Learning models (LSTM / BERT)
* Create a web interface using Flask or Streamlit
* Deploy the model online

---

## 👨‍💻 Author

Raghavendra (AI & Data Science Student)

This project is created for learning **Machine Learning and NLP concepts using Python**.
# fake-news-detection
