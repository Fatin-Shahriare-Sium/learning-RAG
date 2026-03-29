# 🚀 Learning RAG (Retrieval-Augmented Generation)

A hands-on project to understand and implement **Retrieval-Augmented Generation (RAG)** using embeddings, vector databases, and LLM pipelines.

---

## 📌 Overview

This project demonstrates how to build a **RAG system from scratch**, including:

- 📄 Document ingestion & chunking  
- 🔢 Embedding generation  
- 🧠 Vector search using FAISS  
- 🤖 Context-aware response generation  

---

## 🧠 What is RAG?

**Retrieval-Augmented Generation (RAG)** works in three steps:

1. Retrieve relevant documents  
2. Pass them to an LLM  
3. Generate accurate, context-aware answers  

---

## ⚙️ Features

- ✅ Custom FAISS vector store  
- ✅ Text chunking with overlap  
- ✅ SentenceTransformer embeddings  
- ✅ Persistent vector storage  
- ✅ Modular design  

---

## 🏗️ Project Structure

learning-RAG/
├── src/
│ ├── embedding.py
│ └── vector_store.py
├── faiss_store/
├── data/
├── main.py
├── requirements.txt
└── README.md

---

## 🔄 How It Works
User Query
↓
Embedding
↓
FAISS Search
↓
Relevant Chunks
↓
LLM Response


---

## 🛠️ Installation

```bash
git clone https://github.com/Fatin-Shahriare-Sium/learning-RAG.git
cd learning-RAG

python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Linux/Mac

pip install -r requirements.txt

▶️ Usage
python main.py
```
## 🧩 Core Components

### 🔹 Embedding Pipeline
- Converts text into vector embeddings  
- Model: `all-MiniLM-L6-v2`

### 🔹 Vector Store (FAISS)
- Stores embeddings  
- Performs similarity search  
- Supports saving/loading index  

### 🔹 Retrieval
- Finds most relevant chunks  
- Improves answer quality  

---

## 📈 Future Improvements
- Add LLM integration  
- Build API (FastAPI)  
- Add UI (Next.js / Streamlit)  
- Hybrid search  

---

## 🎯 Learning Goals
- Understand RAG deeply  
- Learn embeddings & vector DBs  
- Build real-world AI pipelines  
