# 🧠 Virtual TA – TDS Project One

This project is a **RAG-based (Retrieval-Augmented Generation)** assistant that serves as a **Virtual Teaching Assistant (Virtual TA)** for the **TDS Knowledge Base** from IITM's online degree forum. It scrapes course-related discussions, processes them, and enables semantic search and intelligent Q&A over the data using modern LLM techniques.

---

## 🚀 Features

- 🔍 Scrapes data from [IITM Discourse Forum](https://discourse.onlinedegree.iitm.ac.in/)
- 🧹 Preprocesses and cleans all discussion threads
- 📚 Stores context in a vector database for fast retrieval
- 🤖 Provides a local API for intelligent Q&A over the data (RAG)
- 📦 Simple FastAPI backend with `/query` and `/health` endpoints

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/22f1001281/tds-project-one_virtual-ta.git
cd tds-project-one_virtual-ta
