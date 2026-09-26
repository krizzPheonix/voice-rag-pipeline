# 🎙️ Enterprise Voice-RAG AI Pipeline

An advanced, voice-enabled Retrieval-Augmented Generation (RAG) system designed to securely search and answer questions from custom technical documents. Built with a FastAPI backend and FAISS vector search, this pipeline allows users to query dense knowledge bases (like supply chain policies, technical manuals, or corporate rulebooks) using natural speech and receive real-time, AI-grounded audio responses.

## 🚀 Quick Start

1. **Install Python 3.8+** (Recommended: Python 3.11+)
2. **Clone and setup:**
   ```bash
   git clone <your-repository-url>
   cd voice-rag-pipeline
   
   # Create virtual environment
   python -m venv venv
   venv\Scripts\activate  # On Windows
   
   # Install dependencies
   pip install -r requirements.txt