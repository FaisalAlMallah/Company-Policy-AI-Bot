# Company-Policy-AI-Bot

This project implements a local Retrieval Augmented Generation (RAG) system in Python. It allows you to ask natural language questions about company policies and receive contextually relevant answers.

**Core Technologies:**
*   LangChain for orchestration
*   HuggingFace Sentence Transformers (`all-MiniLM-L6-v2`) for embeddings
*   ChromaDB for local vector storage
*   Locally run Llama 2 7B (via `LlamaCpp`) for answer generation
