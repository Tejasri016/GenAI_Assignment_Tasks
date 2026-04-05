# 🧠 NLP Assignment – Token Classification (POS Tagging)

## 📌 Objective
The objective of this project is to build and fine-tune a transformer-based model (BERT) for **Part-of-Speech (POS) Tagging** using token classification techniques.

---

## 🛠️ Tools & Technologies
- Python
- Hugging Face Transformers
- Datasets
- PyTorch
- SeqEval

---

## 📂 Dataset
A **custom dataset** was created manually for POS tagging due to compatibility issues with external datasets in the latest environment.

### Example:
| Tokens | Labels |
|-------|--------|
| John works at Google | NOUN VERB ADP NOUN |
| She is reading a book | PRON VERB VERB DET NOUN |

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing
- Tokenized sentences using BERT tokenizer
- Handled subword tokenization
- Aligned labels using `-100` for special tokens

### 2️⃣ Model Setup
- Used `bert-base-uncased`
- Applied `AutoModelForTokenClassification`
- Defined label mappings (`label2id`, `id2label`)

### 3️⃣ Training
- Learning Rate: `2e-5`
- Epochs: `5`
- Batch Size: `4`

### 4️⃣ Evaluation
- Metric: **SeqEval**
- Evaluated using:
  - Precision
  - Recall
  - F1 Score

---

## 📊 Results

| Metric | Value |
|--------|------|
| Precision | XX |
| Recall | XX |
| F1 Score | XX |

> Replace XX with your actual results

---

## 🔍 Inference Example

**Input:**
