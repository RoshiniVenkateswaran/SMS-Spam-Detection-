# 📦 Spam Message Detection using Naive Bayes

This project builds a **Spam Message Classifier** using the **Naive Bayes algorithm** and **CountVectorizer** from Scikit-learn.  
The model classifies SMS messages as either **Spam** or **Ham (Not Spam)**.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Results](#results)
- [Example Predictions](#example-predictions)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🧠 Overview

This project demonstrates how to build a **text classification model** using **Natural Language Processing (NLP)** techniques.  
We use a **Naive Bayes Classifier (MultinomialNB)**, which works great for text data because it assumes independence between features (words).

Messages are vectorized using **CountVectorizer**, which converts text into a bag-of-words representation.

---

## 🧾 Dataset

The dataset used is the **SMS Spam Collection Dataset** from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

| Column | Description |
|---------|-------------|
| `v1` | Label — "ham" (not spam) or "spam" |
| `v2` | Message text |

We rename the columns for clarity:
- `label` → text label (“ham” or “spam”)  
- `message` → SMS text  
- `label_num` → numeric label (`0` for ham, `1` for spam`)

---

## ⚙️ Installation

Clone this repository:
```bash
git clone https://github.com/your-username/spam-message-detector.git
cd spam-message-detector
