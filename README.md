# 📧 Spam Email Classifier (NLP + Machine Learning)

A machine learning project that classifies emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and the Naive Bayes algorithm.

---

## 🚀 Features

* 📩 Classifies emails into Spam or Ham
* 🧠 Uses NLP techniques for text processing
* ⚡ Fast and efficient with Naive Bayes algorithm
* 🔍 Text preprocessing for improved accuracy
* 🎯 Beginner-friendly ML project

---

## 🛠 Tech Stack

* **Python**
* **scikit-learn**
* **Pandas**
* **NumPy**

---

## 📁 Project Structure

```id="q1mzn2"
spam_classifier/
│── app.py / main.py      # Main script
│── spam.csv              # Dataset
│── requirements.txt      # Dependencies
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash id="w2ms4z"
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier
```

---

### 2️⃣ Install Dependencies

```bash id="x93ldk"
pip install -r requirements.txt
```

---

### 3️⃣ Run the Project

```bash id="y4fdl1"
python main.py
```

---

## 💡 How It Works

1. Load dataset containing email messages
2. Preprocess text:

   * Convert to lowercase
   * Remove punctuation
   * Remove stopwords
3. Convert text → numerical features using **CountVectorizer / TF-IDF**
4. Train model using **Naive Bayes algorithm**
5. Predict whether email is Spam or Ham

---

## 🧠 Machine Learning Pipeline

* Text Cleaning
* Feature Extraction (Bag of Words / TF-IDF)
* Model Training (Naive Bayes)
* Evaluation (Accuracy Score)

---

## 📊 Example Output

| Email Text                  | Prediction |
| --------------------------- | ---------- |
| "Win a free iPhone now!!!"  | Spam       |
| "Meeting at 10 AM tomorrow" | Not Spam        |


---

## 📌 Resume Highlight

> Developed a Spam Email Classifier using NLP techniques and Naive Bayes algorithm, improving classification accuracy through text preprocessing and feature extraction.

---

## ⚠️ Important Notes

* Dataset should be clean for better accuracy
* Text preprocessing plays a major role in performance
* Naive Bayes works well for text classification tasks

