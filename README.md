# 🕵️ Review Guard: Fake Review Detection System

## 📌 Project Overview

The **Fake Review Detection System** is a locally runnable web application that uses Natural Language Processing (NLP) to classify online reviews as **genuine** or **fake**.

Users can:

* Analyze a single review text
* Upload a CSV file for batch analysis
* View predictions with confidence percentages
* Run the system fully offline (no cloud required)

This project was developed by a three-person academic team over 10 weeks (part-time, $0 budget).

---

## 🎯 Project Goals

* **Technical Goal:** Achieve >80% classification accuracy on a held-out test set.
* **Process Goal:** Deliver a functioning local web application using Agile methodology with four milestones.

---

## 🛠️ Key Features

* Single review classification
* Batch CSV review processing
* Confidence score output
* Offline execution
* Simple web interface

---

## 🧠 Technology Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS, JavaScript
* **ML/NLP:** Scikit-learn, NLTK
* **Data Processing:** Pandas

---

## 📂 Project Structure

```
fake-review-detection/
│
├── app/
│   ├── templates/
│   ├── static/
│   └── main.py
│
├── model/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── requirements.txt
└── README.md
```

---

## 🚀 Installation & Run

```bash
# Clone repository
git clone https://github.com/kritisubedi1/review-guard.git
cd review-guard

cd backend

# Install dependencies
pip install -r requirements.txt

# Run application
python run.py
```

Open: `http://localhost:5000`

---

## 📊 Model Evaluation

* Accuracy (>80% target)
* Precision, Recall, F1-Score

---

## 📅 Agile Milestones

1. Planning & Dataset Preparation
2. Model Development
3. Web Application Integration
4. Testing & Final Delivery

---

## 📜 License

Developed for academic purposes.
