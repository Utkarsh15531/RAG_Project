
# Retrieval-Augmented Generation (RAG) – Mini Project

## Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline to enhance the accuracy and reliability of LLM (Large Language Model) responses by grounding them in retrieved context from external documents.
It covers all essential components — from data ingestion and embedding generation to retrieval, prompt design, and response generation — forming a modular and production-ready RAG system.


## Objectives
Understand the core architecture of a RAG system.
Build a complete data ingestion pipeline for text/PDF documents.
Implement document chunking, embedding generation, and vector storage using FAISS/Chroma.
Design retrieval and LLM integration pipelines for context-aware responses.
Explore prompt engineering techniques to improve LLM performance.
Structure the project for modularity and scalability.

## Tech Stack

Language: Python
Libraries: LangChain, FAISS / Chroma, OpenAI API, Hugging Face
Environment: Jupyter Notebook / VS Code
LLM Used: OpenAI GPT-3.5 / GPT-4

## File Structure
```bash
├── data/                    # Sample PDFs and text files
├── ingestion_pipeline.py     # Handles document loading & chunking
├── embedding_pipeline.py     # Converts text chunks to embeddings
├── vectorstore.py            # Stores embeddings in FAISS/Chroma
├── retrieval_pipeline.py     # Retrieves relevant chunks for a query
├── rag_function.py           # Combines retrieval with LLM response
├── app.py                    # (Optional) Runs the complete RAG app
└── README.md                 # Project documentation
```


## Key Features

🔹 End-to-end RAG pipeline: From raw data to LLM response
🔹 Chunking and vectorization for efficient retrieval
🔹 Context-aware response generation
🔹 Prompt templates for accurate and grounded answers
🔹 Modular design — easy to extend with new data sources or models

## Learning Outcomes

Gained practical understanding of how retrieval improves LLM reliability.
Developed hands-on skills with LangChain and vector databases.
Learned prompt engineering for context injection and response optimization.
Structured the code for reusability and scalability in real-world applications.

## Future Enhancements

Integrate UI for user queries (e.g., Streamlit/Gradio).
Add real-time document updates in vector store.

Deploy as a RAG chatbot API for knowledge retrieval.

## Author

Utkarsh Arya
Bachelors in Mathematics and Computing, IIT Patna
