# 📚 RAG Book Assistant

A Retrieval-Augmented Generation (RAG) application that enables users to upload PDF documents and ask natural language questions about their content. The system combines **LangChain**, **Mistral AI**, **ChromaDB**, and **semantic search** to provide context-aware, document-grounded responses.

---

## 🚀 Features

- 📄 Upload and process PDF documents
- 🔍 Semantic document retrieval using vector embeddings
- 🤖 Question Answering powered by Mistral AI
- 🧠 Retrieval-Augmented Generation (RAG)
- 📚 Chroma Vector Database for efficient document search
- ✂️ Intelligent document chunking
- ⚡ Interactive Streamlit interface
- 💬 Context-aware responses generated only from the uploaded document

---

## 🧠 RAG Pipeline

```
PDF Document
      │
      ▼
PyPDFLoader
      │
      ▼
Recursive Text Splitting
      │
      ▼
Mistral Embeddings
      │
      ▼
Chroma Vector Database
      │
      ▼
Retriever (MMR Search)
      │
      ▼
Relevant Context
      │
      ▼
Mistral LLM
      │
      ▼
AI Answer
```

---

## 🛠 Tech Stack

### Programming Language

- Python

### Generative AI

- LangChain
- Mistral AI

### Retrieval-Augmented Generation

- ChromaDB
- Mistral AI Embeddings
- RecursiveCharacterTextSplitter
- PyPDFLoader

### Frontend

- Streamlit

### Environment Management

- Python Dotenv

---

## 📚 AI Concepts Demonstrated

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings
- Vector Databases
- Similarity Search
- Maximum Marginal Relevance (MMR)
- Prompt Engineering
- Context-Aware Question Answering
- Large Language Models (LLMs)

---

## 💡 How It Works

1. Upload a PDF document.
2. The document is loaded using **PyPDFLoader**.
3. The text is divided into overlapping chunks using **RecursiveCharacterTextSplitter**.
4. Each chunk is converted into vector embeddings using **Mistral AI Embeddings**.
5. Embeddings are stored in **ChromaDB**.
6. When a question is asked, the retriever fetches the most relevant chunks using **Maximum Marginal Relevance (MMR)**.
7. Retrieved context is combined with the user's query and sent to **Mistral AI**.
8. The model generates an answer grounded in the retrieved document context.

---

## 📖 Skills Demonstrated

- Generative AI
- Retrieval-Augmented Generation (RAG)
- LangChain
- Large Language Models (LLMs)
- Prompt Engineering
- ChromaDB
- Vector Embeddings
- Semantic Search
- Mistral AI
- Streamlit
- Python

---

## 🎯 Future Improvements

- ChatGPT-style conversational interface
- Multi-document support
- Source citations with page numbers
- Streaming responses
- PDF highlighting
- Chat history
- FAISS and Pinecone integration
- Hybrid Search (Keyword + Semantic)
- React + FastAPI deployment
- Authentication & User Sessions

---

## 👨‍💻 Author

**Akshat Mishra**

B.Tech in Data Science & Artificial Intelligence  
Thapar Institute of Engineering & Technology

---

⭐ If you found this project useful, consider giving it a star!