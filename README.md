🚀 Learning RAG (Retrieval-Augmented Generation)

A hands-on project to understand and implement Retrieval-Augmented Generation (RAG) using modern NLP tools like embeddings, vector databases, and LLM pipelines.

📌 Overview

This repository demonstrates how to build a RAG system from scratch, combining:

📄 Document ingestion & chunking
🔢 Embedding generation
🧠 Vector search using FAISS
🤖 Context-aware response generation

RAG improves LLM outputs by retrieving relevant external knowledge instead of relying only on pre-trained data .

🧠 What is RAG?

Retrieval-Augmented Generation (RAG) is a technique where:

Relevant documents are retrieved from a knowledge base
These documents are passed to an LLM
The LLM generates more accurate and grounded responses

👉 This helps reduce hallucination and improves factual correctness.

⚙️ Features
✅ Custom FAISS vector store implementation
✅ Text chunking with overlap
✅ Embedding pipeline using SentenceTransformers
✅ Persistent storage for vectors
✅ Modular and extensible architecture
✅ Easy to plug into any LLM (OpenAI, local models, etc.)
🏗️ Project Structure
learning-RAG/
│── src/
│   ├── embedding.py        # Embedding pipeline
│   ├── vector_store.py     # FAISS vector DB implementation
│
│── faiss_store/            # Saved vector index
│── data/                   # Input documents
│── main.py                 # Entry point
│── requirements.txt
│── README.md
🔄 How It Works
User Query
   ↓
Embedding
   ↓
Vector Search (FAISS)
   ↓
Relevant Chunks Retrieved
   ↓
LLM Generates Answer
🛠️ Installation
# Clone the repository
git clone https://github.com/Fatin-Shahriare-Sium/learning-RAG.git

# Move into project folder
cd learning-RAG

# Create virtual environment
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)

# Install dependencies
pip install -r requirements.txt
▶️ Usage
python main.py

You can:

Add your own documents inside /data
Modify chunk size & overlap
Replace embedding models
Plug in any LLM API
🧩 Core Components
🔹 Embedding Pipeline
Converts text → vector embeddings
Uses models like:
all-MiniLM-L6-v2
🔹 Vector Store (FAISS)
Stores embeddings efficiently
Enables fast similarity search
Supports persistence (save/load index)
🔹 Retrieval System
Finds most relevant chunks for a query
Uses similarity search (cosine / L2)
📈 Future Improvements
 Add LLM integration (OpenAI / Ollama)
 Build API using FastAPI
 Add UI (Streamlit / Next.js)
 Hybrid search (BM25 + vector)
 Evaluation metrics
🎯 Learning Goals

This project is built to:

Understand how RAG works internally
Avoid over-reliance on frameworks like LangChain
Learn vector databases + embeddings deeply
Build production-ready AI pipelines
🤝 Contributing

Contributions are welcome!

# Fork the repo
# Create a branch
# Make changes
# Submit a PR
📄 License

This project is open-source and available under the MIT License.

🙋‍♂️ Author

Fatin Shahriare Sium
💻 Passionate about AI, Web, and Real-world problem solving

⭐ Support

If you found this useful:

⭐ Star the repo
🍴 Fork it
🧠 Share with others learning RAG
