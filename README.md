Agentic RAG System: AI-Powered Legal Contract Assistant
📋 Overview
The Agentic RAG System is a next-generation document intelligence platform. Unlike traditional RAG systems that only provide information, this "Agentic" version performs goal-oriented tasks. Specifically designed for legal contexts, it analyzes complex PDF contracts, identifies hidden risks, and executes follow-up actions like drafting executive summaries and risk-assessment emails.

✨ Key Features
Intelligent PDF Ingestion: Automated text extraction and semantic chunking with metadata retention.

Vector-Based Retrieval: High-accuracy semantic search using OpenAI Embeddings and ChromaDB.

Automated Risk Analysis: An AI agent that categorizes legal risks by severity (High, Medium, Low) and suggests mitigation strategies.

Actionable Outputs: One-click generation of professional email drafts summarizing key findings.

Real-time Streaming: Smooth, low-latency AI responses using Server-Sent Events (SSE).

Audit Trail: An "Action History Log" that tracks every query, analysis, and draft generated for compliance.

🛠️ Technical Stack
Core Logic: Python, LangGraph / LangChain

LLM: OpenAI GPT-4o / Llama 3 (via Ollama)

Database: ChromaDB (Vector Store), PostgreSQL (Metadata & Logs)

API: FastAPI

Frontend: Streamlit / React with Tailwind CSS

🌍 Real-World Application
In modern legal and corporate environments, professionals are overwhelmed by documentation. This system is applicable in:

Legal Firms: Rapidly auditing thousands of pages for "change-of-control" or "indemnity" clauses.

Procurement: Automating the comparison of vendor contracts against company policy.

Real Estate: Quickly identifying unfavorable terms in lease agreements.

🚀 Getting Started
Prerequisites
Python 3.10+

OpenAI API Key

Installation
Clone the repo:

Bash


Bash

pip install -r requirements.txt
Configure Environment: Create a .env file and add your OPENAI_API_KEY.
Run the Application:

Bash

uvicorn main:app --reload
