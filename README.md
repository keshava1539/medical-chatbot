## Medical Chatbot with RAG System
## 📊 Overview
-This project develops an AI-powered medical chatbot leveraging a Retrieval Augmented Generation (RAG) architecture. The chatbot is designed to provide accurate and contextually relevant answers to medical inquiries by dynamically retrieving information from a curated knowledge base of PDF documents and synthesizing responses using a Large Language Model. This approach significantly reduces hallucinations and enhances the reliability of the generated information.

## 🧠 Project Highlights
-Intelligent Q&A: Answers medical questions based on factual information from provided PDF documents.

-RAG Architecture: Implements a robust RAG pipeline for enhanced accuracy and context awareness.

-Efficient Information Retrieval: Utilizes a Pinecone vector database for fast and semantically relevant document chunk retrieval.

-Data Processing Pipeline: Includes modules for loading, splitting, and embedding text from PDF documents.

-LLM Integration: Seamlessly integrates with powerful language models to generate coherent and informative responses.

## 🔍 Techniques & Technologies Used
-Python

-LangChain (for orchestrating the RAG pipeline)

-Pinecone (Vector Database for semantic search)

-HuggingFace Embeddings (sentence-transformers/all-MiniLM-L6-v2 for text vectorization)

-LangChain OpenAI (interface for connecting to LLMs, e.g., DeepSeek via Fireworks AI endpoint)

-PyPDFLoader (for document ingestion)

-RecursiveCharacterTextSplitter (for efficient text chunking)

## 📁 Files
-model.ipynb: The main Jupyter Notebook containing the code for the RAG pipeline, including PDF loading, text processing, embedding generation, vector store interaction, and the QA chain setup.

-data/: Directory expected to contain the PDF documents that form the knowledge base for the chatbot.
