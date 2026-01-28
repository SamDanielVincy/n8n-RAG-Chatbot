# 🚀 n8n RAG Chatbot using Gemini & Supabase

An end-to-end **Retrieval-Augmented Generation (RAG) chatbot** built using **n8n automation**, **Google Gemini models**, and **Supabase Vector Store**.

This project demonstrates how modern AI systems combine **automation, embeddings, vector databases, and LLM agents** to deliver accurate, context-aware responses.

---

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

## 📂 Repository Structure

