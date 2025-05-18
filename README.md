# Text Classification using Machine Learning and NLP

## Overview
This project implements text classification using multiple machine learning models. The dataset undergoes preprocessing using the `spaCy` library, followed by feature extraction using TF-IDF vectorization. The classification is performed using four different algorithms:

- **Naïve Bayes**
- **Random Forest**
- **J48 (Decision Tree)**
- **Support Vector Machine (SVM)**

## Dataset
The dataset contains:
- **Sentence:** The text that needs to be classified.
- **Ground Polarity:** The target labels for classification.

## Preprocessing Steps
The text data is preprocessed using the following steps:
1. **Lowercasing**
2. **Removing Punctuation**
3. **Tokenization and Lemmatization** (using `spaCy`)
4. **Stop-word Removal**

## Feature Extraction
- **TF-IDF (Term Frequency - Inverse Document Frequency)** is applied to convert text into numerical features.

## Model Training and Evaluation
Each model is trained on the dataset and evaluated based on:
- **Precision**
- **Recall**
- **F1-score**
- **Macro F1-score**

## Installation
To run this project, install the required dependencies:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## Execution
Launch the notebook:

```bash
jupyter notebook text_classification.ipynb
```

## Results
The performance of each model is displayed in a tabular format at the end of execution.

## Authors
Developed by **Qaisar Manzoor**.

---
For any queries, feel free to reach out!
