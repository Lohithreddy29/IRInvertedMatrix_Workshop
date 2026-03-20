

# **IR Inverted Matrix Workshop**

This repository contains an interactive workshop for building a foundational Information Retrieval (IR) system using inverted indexes, positional indexes, TF/IDF scoring, and simple query processors. The notebook walks through each IR component step‑by‑step to demonstrate how search engines process and retrieve text.

---

## **📘 What’s Included**

- **IR_InvertedMatrix_Workshop.ipynb** — complete notebook covering:
  - Corpus loading  
  - Tokenization  
  - Text normalization  
  - Inverted index construction  
  - Positional index construction  
  - Phrase & bigram search  
  - TF, DF, IDF  
  - TF–IDF comparison  
  - Query processor implementation  

- **sample_docs/** — text files used as the document corpus.

- **requirements.txt** — minimal Python dependencies.


---

## **🔧 Setup**

```
python -m venv venv
venv\Scripts\activate   # Windows
# venv/bin/activate     # macOS/Linux

pip install -r requirements.txt
```

---

## **▶️ Running the Notebook**

1. Start Jupyter Notebook:
   ```
   jupyter notebook IR_InvertedMatrix_Workshop.ipynb
   ```
2. Run all cells in order.  
3. Modify or add files inside `sample_docs/` to test indexing and query behavior.

---

## **🧪 Lab Tasks**

- Load and preprocess documents  
- Tokenize text, remove stopwords, and apply stemming (NLTK)  
- Build an **inverted index** (term → document list)  
- Build a **positional index** (term → document → positions)  
- Compute **TF**, **DF**, and **IDF**  
- Compare **TF vs IDF** using a simple table  
- Implement **phrase search** and **bigram search**  
- Build a **query processor** to retrieve matching documents  
- Evaluate results using sample queries  

---

## **📌 Notes**

- `requirements.txt` includes:
  - `requests`
  - `feedparser`
  - `nltk`
  - `pandas`
- If you install additional packages inside the notebook, update `requirements.txt` manually.

---

## **🗂️ Directory Structure**

```
IRInvertedMatrix_Workshop/
│
├── IR_InvertedMatrix_Workshop.ipynb
├── requirements.txt
├── README.md
│
├── sample_docs/
│   └── (text files)

```

---
 section, I can prepare that in the same clean style.


