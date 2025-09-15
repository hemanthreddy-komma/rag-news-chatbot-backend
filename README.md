# RAG News Chatbot - Backend

## Overview
This is the backend service for the **RAG News Chatbot** application. It provides RESTful APIs for user authentication, document uploads, content management, and AI-powered chat using OpenAI models.

---

## Features
- User authentication (JWT-based)
- PDF, text, URL, and YouTube content ingestion
- Semantic search with Qdrant vector database
- AI-powered chat with context-aware responses
- Notebook and content management
- Credit-based usage tracking
- Email notifications (registration, verification, password reset)

---

## Technology Stack
- **Node.js** (v18+)
- **Express.js** (Web framework)
- **MongoDB** (Database)
- **Mongoose** (ODM)
- **OpenAI API** (GPT-4.1, embeddings)
- **Qdrant** (Vector database)
- **Multer** (File uploads)
- **JWT** (Authentication)
- **Nodemailer** (Email services)
- **LangChain** (AI content processing)

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/hemanthreddy-komma/rag-news-chatbot-backend.git
cd rag-news-chatbot-backend
