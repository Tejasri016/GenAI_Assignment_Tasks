# 🧠 NLP Preprocessing Engine
## 📌 Overview

This project focuses on building a robust Natural Language Processing (NLP) preprocessing pipeline to handle messy real-world text data.
The goal is to convert raw, unstructured text into clean and meaningful tokens that can be used for machine learning models.

## 🎯 Objectives
Clean noisy text data (URLs, emojis, numbers, etc.)
Normalize text for consistency
Perform token-level analysis
Build a reusable preprocessing pipeline
## ⚙️ Features Implemented
✅ Convert text to lowercase
✅ Remove URLs and email patterns
✅ Remove numbers
✅ Handle repeated characters (e.g., "soooo" → "soo")
✅ Remove special characters and emojis
✅ Remove extra spaces
✅ Filter short words (keeping important ones like "no", "not")
✅ Tokenization
✅ Frequency analysis using Counter
✅ Token analytics (count, unique, average length)
✅ Error handling for edge cases
## 🧪 Sample Input
"I absolutely looooved this product 😍😍"
✅ Output
Tokens: ['absolutely', 'looved', 'this', 'product']
Cleaned Sentence: absolutely looved this product
## 📊 Token Analytics

For each sentence, the following are calculated:

Total number of tokens
Unique tokens
Average token length
## 📈 Frequency Analysis
Top 10 most frequent words
Least frequent words
## 🔁 Full Pipeline Function

The project also includes a reusable function:

run_full_pipeline(data)
Returns:
Combined tokens
Cleaned sentences
## ⚠️ Edge Cases Handled
Empty string
Only emojis
Only numbers
## 🛠️ Technologies Used
Python
Regular Expressions (re)
Collections (Counter)
Jupyter Notebook / Google Colab

## 🚀 How to Run
- Open the notebook in Jupyter or Google Colab
- Run all cells step by step
- Check outputs for preprocessing and analysis

