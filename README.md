# DocuMind AI

## 📘 Intelligent Document Assistant

DocuMind AI is a Streamlit-powered application that allows users to upload PDF research documents and ask queries related to the content. The app processes the document, indexes it using vector embeddings, and provides relevant answers using an LLM.

---

## 🚀 Features
- Upload a PDF document for analysis.
- Automatically processes and indexes document content.
- Ask questions and receive AI-generated answers based on the document.
- Dark-themed UI with a chat-style interface.
- Uses **DeepSeek-R1 (1.5B)** LLM for responses.
- **In-memory vector store** for document search.

---



## 📂 Project Structure
```
📦 DocuMind AI
├── app.py               # Main Streamlit application
├── document_store/
│   ├── pdfs/           # Folder to store uploaded PDFs
├── README.md            # Project documentation
```

---

## 🔍 How It Works
1. **Upload a PDF** - The document is processed and stored.
2. **Chunking & Indexing** - Text is split into chunks and indexed for search.
3. **Querying** - User inputs a query, and the app finds the most relevant text.
4. **AI Response** - DeepSeek-R1 LLM generates a concise response.

---


