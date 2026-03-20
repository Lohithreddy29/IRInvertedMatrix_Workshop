# IR Inverted Matrix Workshop

This repository contains an interactive workshop to build a basic Information Retrieval (IR) system with an inverted index and query processors.

## ✅ What is included
- IR_InvertedMatrix_Workshop.ipynb: main notebook walks through: corpus collection, tokenizer, text normalization, inverted index, TF/IDF scoring, phrase search, and evaluation.
- sample_docs/: pre-downloaded text files used as the corpus.
- equirements.txt: minimal Python dependencies for the workshop.
- utils/: helper scripts for notebook validation and submission.

## 🔧 Setup
`powershell
python -m venv venv
venv\Scripts\activate  # Windows
# venv/bin/activate  # macOS/Linux
pip install -r requirements.txt
`

## ▶️ Run
1. Launch Jupyter Notebook:
   `powershell
jupyter notebook IR_InvertedMatrix_Workshop.ipynb
`
2. Execute cells sequentially.
3. Adjust sample_docs/, run the indexing pipeline and query tests.

## 🧪 What to do in the lab
- Collect or load documents from sample_docs/
- Implement tokenization, stopword removal, stemming using NLTK
- Build a term-document inverted index with positions
- Compute TF, DF, and TF-IDF weights
- Execute sample queries for document ranking
- Compare results with expected behavior in notebook notes

## 📌 Notes
- equirements.txt now only includes:
  - equests
  - eedparser
  - 
ltk
  - pandas
- If you add new packages in notebook, update equirements.txt accordingly.

## 🗂️ Directory structure
- IR_InvertedMatrix_Workshop.ipynb
- equirements.txt
- sample_docs/
- utils/
- README.md

