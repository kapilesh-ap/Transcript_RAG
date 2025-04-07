# 🧠 Transcript RAG Processor

An AI-powered application to upload, analyze, and extract structured information from transcripts using a RAG (Retrieval-Augmented Generation) pipeline. Built with **FastAPI**, **React**, and integrated with **Pinecone**, **HuggingFace**, and **Groq** LLM APIs.

---

## 🚀 Features

- 📤 Upload `.txt` or `.docx` transcripts
- 📦 Store and embed data into Pinecone vector DB
- 🔍 Run prompt-based queries using LLMs
- 📋 View history of processed transcripts
- 🧠 Auto-generates:
  - Summary
  - Task List
  - Structured JSON output
- 🔌 Prompt registry for dynamic prompt injection

---

## 🛠️ Tech Stack

### Backend
- Python, FastAPI
- Pinecone (vector DB)
- LangChain (text splitting)
- HuggingFace (embeddings)
- Groq (LLM completions)
- dotenv, UUID, hashlib

### Frontend
- React (with functional components & hooks)
- Lucide icons
- Axios (for API calls)
- Custom skeletons, drag-drop upload, and error boundaries

---

