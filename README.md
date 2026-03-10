# AI Resume Analyzer using RAG

## Project Overview

This project is an **AI-powered Resume Analyzer** that processes multiple resumes and allows users to query information about candidates using a Retrieval Augmented Generation (RAG) system.

The system extracts text from resumes, creates embeddings, stores them in a vector database, and retrieves relevant information to answer user queries.

## Features

* Resume parsing from PDF files
* Text chunking for better retrieval
* Vector database using FAISS
* Semantic search across resumes
* LLM-based answer generation

## Tech Stack

* Python
* LangChain
* HuggingFace Embeddings
* FAISS
* PyPDFLoader
* Groq LLM

## Architecture

PDF Resumes → Text Extraction → Chunking → Embeddings → Vector Database → Retrieval → LLM Response

## Installation

```bash
pip install langchain faiss-cpu sentence-transformers pypdf groq
```

## Usage

1. Upload resumes in PDF format.
2. Extract and split the resume text into chunks.
3. Generate embeddings and store them in FAISS.
4. Ask questions about candidates.

Example queries:

* "Which candidate has experience in Python?"
* "Who has worked with machine learning?"

## Future Improvements

* Candidate ranking system
* Skill extraction
* Job description matching
* Web interface using Streamlit
* Integration with ATS systems
