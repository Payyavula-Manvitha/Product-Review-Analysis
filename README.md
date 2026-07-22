# 📝 Transformer-Based Product Review Summarization and Rating Prediction

A Natural Language Processing project that performs **abstractive product review summarization** using a fine-tuned **T5 Transformer** model and predicts review ratings using **BERT embeddings** with a Transformer-based classifier.

---

## 📌 Overview

Product reviews often contain lengthy descriptions, making it difficult for customers to quickly understand the overall opinion of a product.

This project aims to:

- Generate concise summaries of product reviews using a fine-tuned T5 model.
- Predict product ratings from the generated summaries using contextual BERT embeddings.
- Demonstrate parameter-efficient fine-tuning using **LoRA (PEFT)** and **BitsAndBytes quantization**.

---

## 🚀 Features

- Abstractive Text Summarization
- T5 Transformer Fine-tuning
- LoRA (Low-Rank Adaptation)
- PEFT
- BitsAndBytes Quantization
- BERT Embeddings
- Transformer-based Rating Prediction
- ROUGE Evaluation Metrics
- PyTorch & Hugging Face Transformers

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- BitsAndBytes
- BERT
- T5
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Project Workflow

```
Product Reviews
        │
        ▼
Data Preprocessing
        │
        ▼
Fine-tune T5 Model
        │
        ▼
Generate Review Summaries
        │
        ▼
Evaluate using ROUGE
        │
        ▼
Extract BERT Embeddings
        │
        ▼
Transformer Classifier
        │
        ▼
Predict Review Ratings
```

---

## 📊 Model Pipeline

### Step 1
Preprocess the product review dataset by cleaning and tokenizing review text.

### Step 2
Fine-tune a T5 Transformer model for abstractive text summarization.

### Step 3
Apply **LoRA (PEFT)** with **BitsAndBytes quantization** to reduce trainable parameters while maintaining performance.

### Step 4
Generate concise summaries for unseen product reviews.

### Step 5
Evaluate summarization quality using:

- ROUGE-1
- ROUGE-2
- ROUGE-L

### Step 6
Extract contextual embeddings from the generated summaries using **BERT**.

### Step 7
Train a Transformer-based classifier to predict product review ratings.

---

## 📈 Evaluation

Summarization performance was evaluated using:

- ROUGE-1
- ROUGE-2
- ROUGE-L

Rating prediction performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

---

## 📁 Repository Structure

```
Product-Review-Analysis/
│
├── FINAL__nlp.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Payyavula-Manvitha/Product-Review-Analysis.git
```

Move into the project directory

```bash
cd Product-Review-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📚 Future Improvements

- Train on larger review datasets
- Improve ROUGE scores
- Deploy using Streamlit
- Add sentiment analysis
- Experiment with larger LLMs such as FLAN-T5 and Llama

---

## 👩‍💻 Author

**Payyavula Manvitha**

B.Tech Computer Science (AI)

Amrita Vishwa Vidyapeetham

GitHub: https://github.com/Payyavula-Manvitha

LinkedIn: https://www.linkedin.com/in/manvithapayyavula/

---

## ⭐ If you found this project useful, consider giving it a star!
