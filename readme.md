# 🚀 n8n RAG Chatbot using Gemini & Supabase

An end-to-end **Retrieval-Augmented Generation (RAG) chatbot** built using **n8n automation**, **Google Gemini models**, and **Supabase Vector Store**.

This project demonstrates how modern AI systems combine **automation, embeddings, vector databases, and LLM agents** to deliver accurate, context-aware responses.

---
<img width="1873" height="721" alt="Screenshot 2026-01-28 233952" src="https://github.com/user-attachments/assets/0f67d7bf-e482-4c51-a718-44b92594da0f" />



## 🧠 Project Overview

The goal of this project is to build a **fully automated document ingestion and conversational AI system** that can:
- Ingest documents automatically
- Store semantic embeddings
- Retrieve relevant context
- Generate grounded answers using RAG principles

---

## 🏗️ System Architecture

**Two main workflows are implemented:**

### 📥 1. Data Ingestion Workflow
- Downloads files from **Google Drive**
- Processes document content
- Generates embeddings using **Google Gemini Embedding Model (001)**
- Stores vectors in **Supabase Vector Store**

### 💬 2. Chat & Retrieval Workflow
- Uses **n8n AI Agent**
- Powered by **Gemini 2.5 Flash**
- Retrieves relevant context from Supabase
- Generates accurate, context-aware responses

---

## 🔧 Tech Stack

- **Automation:** n8n  
- **LLM:** Google Gemini 2.5 Flash  
- **Embeddings:** Gemini Embedding Model (001)  
- **Vector Database:** Supabase  
- **Storage:** Google Drive  
- **Architecture:** Retrieval-Augmented Generation (RAG)

---
## ⚙️ Setup Instructions

1. Clone the repository
2. Import the workflows into in hte json format as RAG Flow Structure
3. Connect:
   - Google Drive
   - Supabase
   - Google Gemini API
5. Run ingestion workflow before using the chat workflow




## 🤝 Connect

If you're interested in **AI automation, RAG systems, or n8n workflows**, feel free to connect and collaborate.

<a href="https://www.linkedin.com/in/sam-daniel-vincy/" target="_blank">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"
       alt="LinkedIn"
       width="30"
       height="30"/>
  <span style="margin-left: 8px;">Connect with me on LinkedIn</span>
</a>
