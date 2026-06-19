# Cyber Bullying Detection on Social Media using Machine Learning

## 📌 Overview

Cyberbullying has become a major concern with the rapid growth of social media platforms. Harmful online activities such as hate speech, personal attacks, and abusive comments can negatively impact users' mental health and digital safety.

This project implements a **Machine Learning based Cyberbullying Detection System** that automatically identifies offensive and abusive content from social media text using **Natural Language Processing (NLP)** and classification algorithms.

The system analyzes user-generated text, extracts meaningful features, and predicts whether the content contains cyberbullying behavior.

---

## 🚀 Features

* Detects cyberbullying content from social media posts
* NLP-based text preprocessing
* Multiple feature extraction techniques
* Machine learning based classification
* Sentiment analysis of user posts
* User registration and authentication
* Real-time offensive content prediction
* Admin dashboard for monitoring users
* Blocking mechanism for repeated offenders
* Model performance evaluation

---

## 🧠 Machine Learning Approach

The workflow of the system:

```
User Input Text
        ↓
Text Preprocessing
        ↓
Feature Extraction
        ↓
Machine Learning Models
        ↓
Cyberbullying Prediction
        ↓
Result Display
```

---

## 📂 Dataset

The project uses two different datasets:

### 1. Twitter Hate Speech Dataset

* Contains tweets with offensive and hateful language
* Used for detecting explicit cyberbullying patterns

### 2. Wikipedia Personal Attack Dataset

* Contains user comments with personal attacks
* Used for detecting subtle abusive behavior

---

## 🔍 NLP Techniques Used

### Text Preprocessing

* Text cleaning
* Tokenization
* Stop word removal
* Text normalization

### Feature Extraction

#### Bag of Words (BoW)

Converts text into numerical word frequency vectors.

#### TF-IDF

Measures the importance of words based on their frequency in documents.

#### Word2Vec Embeddings

Captures semantic relationships between words.

---

## 🤖 Machine Learning Algorithms

### AdaBoost

Used to improve classification performance by combining multiple weak learners.

### Multinomial Naive Bayes

Used for text classification based on word probability distribution.

### Stochastic Gradient Descent (SGD)

Efficient classifier suitable for large text datasets.

### Support Vector Machine (SVM)

Used for sentiment analysis and classification of emotional tone.

---

## 🏗️ System Modules

## User Module

Users can:

* Create an account
* Login into the system
* Submit posts/comments
* Receive prediction results
* View content analysis feedback

---

## Admin Module

Admin can:

* Monitor registered users
* View offensive content statistics
* Check model performance
* Track offensive post count
* Block repeated offenders

---

## 📊 Results

The proposed system achieved:

* More than **90% accuracy** on Twitter hate speech data
* More than **80% accuracy** on Wikipedia personal attack data

The system successfully identifies harmful online content and supports safer social media interaction.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Framework

* Django

### Machine Learning Libraries

* Scikit-learn
* NumPy
* Pandas

### NLP Libraries

* NLTK

### Frontend

* HTML
* CSS
* JavaScript

### Database

* SQLite / Database integration

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/srilalitha2006/Detection-of-Cyberbullying-on-Social-media-using-Machine-Learning.git
```

### Navigate to Project Folder

```bash
cd Detection-of-Cyberbullying-on-Social-media-using-Machine-Learning
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Django Server

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

---

## 📁 Project Structure

```
Cyberbullying/
│
├── dataset/
│
├── models/
│
├── static/
│
├── templates/
│
├── manage.py
│
├── requirements.txt
│
└── README.md
```

---

## 🧪 Testing

The project was evaluated using:

* Unit Testing
* Integration Testing
* Functional Testing
* System Testing
* User Acceptance Testing

All major functionalities were tested successfully.

---

## 🔮 Future Enhancements

* Real-time integration with social media APIs
* Deep learning models like BERT and LSTM
* Multilingual cyberbullying detection
* Improved context-based detection
* Automated reporting system

---

## 👩‍💻 Contributors

* Maheshwari Patil
* Srilalitha Perumalla
* Bhargavi Kannepati

Department of Computer Science and Engineering in 
CMR Institute of Technology

---

## 📚 References

* Research papers on cyberbullying detection
* NLP based text classification techniques
* Machine learning approaches for hate speech detection

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
