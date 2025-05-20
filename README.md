# 🧠 NLP - Natural Language Processing Toolkit

This repository contains a collection of fundamental and advanced Natural Language Processing (NLP) modules implemented in Python. The goal of this repository is to provide clear and concise implementations of common NLP techniques that serve as building blocks for more complex language understanding systems.

---

## 📂 Repository Structure

The repository includes the following modules:

### 🔠 Morphology

- **Add Table**: Handles morphological transformations and additions (e.g., pluralization, tense conversion).
- **Delete Table**: Handles rules for morphological deletions (e.g., stemming and lemmatization).

### 🔤 N-Gram Model

- Implements unigram, bigram, and trigram models.
- Useful for text generation and language modeling.
- Includes frequency-based probability calculations.

### 🧾 Named Entity Recognition (NER)

- Rule-based and/or model-based implementation of NER.
- Recognizes entities such as `Person`, `Organization`, `Location`, `Date`, etc.
- Trained or tested using spaCy/custom NER models.

### 🧠 NER Model

- Custom NER model built using machine learning or deep learning (e.g., CRF, BiLSTM, spaCy).
- Preprocessing pipeline, training script, and evaluation metrics included.

### 🏷️ Part-of-Speech (POS) Tagging

- POS tagging implementation using either rule-based or statistical models.
- Supports standard tags like `NN`, `VB`, `JJ`, etc.
- Useful for syntactic parsing and downstream NLP tasks.

### 🔗 Semantic Relationships

- Code to extract semantic relationships (e.g., synonymy, antonymy, hypernymy) between words.
- May utilize WordNet, embeddings, or dependency parsing.

---

## 🛠️ Installation

```bash
git clone https://github.com/Vaishnavi639/NLP.git
cd NLP

