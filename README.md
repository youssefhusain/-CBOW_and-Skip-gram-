# Word2Vec - Neural Word Embeddings

## 📚 Overview

This project presents and explains the **Word2Vec** model, a set of neural network-based architectures designed to efficiently learn **word embeddings** from massive text datasets. Two primary architectures are implemented and compared:

- **CBOW (Continuous Bag of Words)**: Predicts the current word based on the context (surrounding words).
- **Skip-gram**: Predicts the surrounding context words given the current word.

These models are capable of capturing **semantic** and **syntactic** relationships between words using simple vector arithmetic.

---

## 🧠 Architectures

### 🔸 CBOW

- **Goal**: Predict the target (current) word based on the context window.
- **Input**: Multiple context words.
- **Output**: A single word (the target).
- **Use case**: Works better with smaller datasets and frequent words.

### 🔹 Skip-gram

- **Goal**: Predict surrounding words given a current word.
- **Input**: A single word.
- **Output**: Multiple context words.
- **Use case**: Works better with larger datasets and rare words.

---

## ⚙️ Advantages

- Faster training compared to earlier embedding techniques.
- Scales well with large corpora.
- Outperforms previous models in word similarity tasks.

---

## 🔍 Applications

- NLP tasks such as text classification, sentiment analysis, machine translation.
- Capturing word relationships such as:
  - `King - Man + Woman = Queen`
  - `Paris - France + Italy = Rome`

