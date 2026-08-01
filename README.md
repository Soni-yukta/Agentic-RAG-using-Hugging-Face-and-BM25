# 🤖 Agentic RAG using Hugging Face and BM25

An Agentic Retrieval-Augmented Generation (RAG) pipeline that combines intelligent document retrieval with Large Language Models (LLMs) to generate context-aware and reliable responses. The project demonstrates how AI agents coordinate retrieval and response generation, reducing hallucinations by grounding answers in relevant documents.

---

## ✨ Features

- Agentic workflow using SmolAgents
- BM25-based intelligent document retrieval
- Custom Retriever Tool integration
- Retrieval-Augmented Generation (RAG)
- LangChain document chunking
- Hugging Face LLM integration
- Context-aware question answering
- Modular and extensible architecture
- Interactive Gradio interface

---

## 🛠️ Tech Stack

- Python
- SmolAgents
- Hugging Face Inference API
- LangChain
- BM25 (rank-bm25)
- Pandas
- Gradio
- Jupyter Notebook

---

## ⚙️ Workflow

### 1. Document Processing
Documents are loaded and split into smaller chunks for efficient retrieval.

### 2. Agentic Query Processing
The AI agent analyzes the user query and decides when to invoke the retrieval tool.

### 3. BM25 Retrieval
Relevant document chunks are retrieved using the BM25 ranking algorithm.

### 4. Response Generation
The retrieved context is supplied to the Hugging Face language model to generate accurate, context-aware answers.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Soni-yukta/Agentic-RAG-using-Hugging-Face-and-BM25.git
cd Agentic-RAG-using-Hugging-Face-and-BM25
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python app.py
```

or execute the Jupyter notebook.

---

## 📊 Example

### Input

```
Which is slower, forward pass or backward pass?
```

### Output

```
Backward propagation is generally slower because gradients are computed for every trainable parameter during training.
```

---

## 📂 Project Architecture

```
User Query
      │
      ▼
Agent (SmolAgents)
      │
      ▼
Retriever Tool
      │
      ▼
BM25 Retrieval
      │
      ▼
Relevant Context
      │
      ▼
Hugging Face LLM
      │
      ▼
Generated Response
```

---

## 🔮 Future Improvements

- Replace BM25 with FAISS vector search
- Hybrid Retrieval (BM25 + Embeddings)
- Cross-Encoder Reranking
- Multi-Agent Collaboration
- Conversation Memory
- Production Deployment using FastAPI

---

## 📜 License

This project is intended for educational and learning purposes.
