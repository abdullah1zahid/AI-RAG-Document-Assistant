# 🤖 Intelligent Document Assistant (RAG System)

This is an advanced AI-powered document assistant built using **n8n**, **OpenAI**, and **Supabase (Vector DB)**. It allows users to upload PDF documents and ask questions in natural language. The system uses RAG (Retrieval-Augmented Generation) to provide accurate answers based strictly on the document content.

## 🚀 Features
- **Automated Ingestion:** Fetches PDF from Google Drive and chunks text automatically.
- **Vector Search:** Uses Supabase Vector Store for high-accuracy semantic search.
- **AI Reasoning:** Powered by OpenAI (GPT-4o) for intelligent summarization and Q&A.
- **Multi-Language Support:** Can explain English documents in Urdu.

## 🛠️ Tech Stack
- **Workflow Automation:** n8n
- **LLM & Embeddings:** OpenAI (GPT-4o, text-embedding-3-small)
- **Vector Database:** Supabase
- **Storage:** Google Drive

## ⚙️ How to Setup
1. Import the `Intelligent_Document_Assistant.json` file into n8n.
2. Run the SQL script provided in `setup.sql` in your Supabase SQL Editor.
3. Configure your OpenAI and Supabase credentials in n8n.
4. Activate the workflow and start chatting!

---
*Created by Abdullah Zahid*
