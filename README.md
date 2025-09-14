# Agentic-RAG-Chatbot
A Retrieval-Augmented Generation (RAG) chatbot for multi-format document question answering, using embeddings, FAISS, and OpenAI’s GPT models. Built with Streamlit for an interactive UI and structured using the Model Context Protocol (MCP) to handle document ingestion, semantic search, and context-aware responses.
# 📚 Agentic RAG Chatbot for Multi-Format Document QA

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that enables users to upload documents (PDF, DOCX, TXT) and ask questions about the content. The chatbot uses embeddings, FAISS vector search, and OpenAI’s GPT models to provide context-aware responses. It is built with Streamlit for an interactive user interface and structured using the Model Context Protocol (MCP).

---

## 🟠 Features

- ✅ Upload and parse documents in PDF, DOCX, TXT formats  
- ✅ Semantic search using embeddings and FAISS for efficient retrieval  
- ✅ Generate answers using OpenAI’s GPT-based models  
- ✅ Structured interaction using the Model Context Protocol (MCP)  
- ✅ Interactive web interface built with Streamlit  
- ✅ Scalable architecture supporting multiple document types  

---

## 🧱 Architecture Overview

The system is composed of multiple agents working together:

1. **Ingestion Agent** – Parses uploaded documents and extracts text.
2. **Retrieval Agent** – Converts text into embeddings and performs similarity search.
3. **LLM Response Agent** – Generates human-like answers based on retrieved content.
4. **Model Context Protocol (MCP)** – Orchestrates the interaction between all agents.
5. **Streamlit UI** – Allows users to upload documents and ask questions easily.

---

## 📦 Technologies Used

- Python 3.x
- Streamlit for UI
- FAISS for vector similarity search
- Sentence Transformers for embeddings
- OpenAI GPT models for answer generation
- PyPDF2, python-docx for document parsing

---

## 🚀 Installation & Setup

### Prerequisites:
- Python 3.8 or later
- An API key for OpenAI or Groq

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rag-chatbot-docqa.git
   cd rag-chatbot-docqa
