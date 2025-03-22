
# 🧠 COVID-19 Tweet Topic Classification with NLP & Deep Learning  

This project focuses on the *automatic classification of COVID-19-related tweets* into categories relevant to combating misinformation. It explores both *traditional machine learning* and *deep learning models* including *Naive Bayes, Logistic Regression, LSTM, and **CNN*.

---

## 🔍 Project Goals
- Develop robust classifiers to label COVID-19 tweets with appropriate topical categories.
- Analyze tweet sentiment and distribution across geography and time.
- Reduce misinformation by enabling real-time content categorization.

---

## 🛠 Technologies Used
- *Python*
- *Natural Language Processing (NLP)*
- *scikit-learn, **Keras, **TensorFlow*
- *Word Embeddings*: GloVe (Twitter pretrained)
- *Models*: Naive Bayes, Logistic Regression, LSTM, CNN
- *Evaluation*: Precision, Recall, F1-Score, Accuracy

## 📊 Key Results
| Model              | Accuracy |
|-------------------|----------|
| Naive Bayes        | 46.9%    |
| Logistic Regression| 61.0%    |
| LSTM               | 69.3%    |
| CNN                | 69.5%    |

- *LSTM and CNN outperformed traditional models*, especially in capturing sentiment context.
- *Logistic Regression* served as a strong baseline for multi-class classification.
- *Overfitting* was observed in deep learning models, indicating need for regularization.

---

## 📌 Dataset
- 41,158 COVID-19 tweets
- Annotated into topics like Symptoms, Medical Advice, Government Policies, and Personal Experiences
- Preprocessing included regex cleaning, stopword removal, lemmatization


## 🚀 Future Improvements
- Introduce BERT-based models for contextual classification
- Improve class balance via data augmentation or synthetic sampling
- Implement explainable AI for model interpretability

