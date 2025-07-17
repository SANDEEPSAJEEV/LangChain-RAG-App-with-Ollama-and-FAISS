# 🧠 GenAI App: LangChain + Ollama (LLama2) + FAISS

This project is a lightweight and functional GenAI app that performs retrieval-augmented generation (RAG) using LangChain. It loads data from a webpage, chunks it, embeds using `Ollama` (LLama2), stores the embeddings in FAISS, and answers questions contextually using a prompt-based LLM pipeline.

---

## 🚀 Features

- 🌐 Loads real-time web data with `WebBaseLoader`
- 🔗 LangChain-powered document chaining and prompting
- 🧠 LLama2 (via Ollama) for fast, local inference
- 🧲 FAISS vectorstore for semantic similarity search
- 🗣️ Retrieval-augmented QA system using a custom chat prompt

---


## 📌 Tech Stack

- **LangChain** – Chain documents & prompts
- **Ollama** – Lightweight local LLM serving (LLama2)
- **FAISS** – Vector search engine
- **OpenAI API (optional)** – Fallback LLMs
- **Python** – Orchestrating everything

---
