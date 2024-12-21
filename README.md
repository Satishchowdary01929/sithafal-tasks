This readme file belongs to both the tasks

# Retrieval-Augmented Generation (RAG) Pipeline and webscraping.

Task-1

# Retrieval-Augmented Generation (RAG) Pipeline

## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline to extract text from PDF files, process and embed the text, store embeddings, and generate detailed responses to user queries using OpenAI's API. 

## System Requirements
### Hardware Requirements
- CPU: Multi-core processor
- RAM: Minimum 8GB
- Storage: Sufficient space to store PDF files and embeddings

### Software Requirements
- Operating System: Windows, macOS, or Linux
- Python: Version 3.6 or above

### Dependencies
- `PyPDF2`
- `sentence-transformers`
- `numpy`
- `openai`
- `os`

You can install these dependencies using pip:
```bash
pip install PyPDF2 sentence-transformers numpy openai

Task-2

## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline using Scrapy for web scraping, Sentence Transformers for embedding text, FAISS for similarity search, and OpenAI's API for generating responses. The goal is to extract text data from university websites, chunk and embed the data, store it for efficient retrieval, and generate responses to user queries.

## System Requirements
### Hardware Requirements
- CPU: Multi-core processor
- RAM: Minimum 8GB
- Storage: Sufficient space to store scraped data and embeddings

### Software Requirements
- Operating System: Windows, macOS, or Linux
- Python: Version 3.6 or above

### Dependencies
- `scrapy`
- `sentence-transformers`
- `numpy`
- `faiss-cpu`
- `openai`
- `json`
- `os`

You can install these dependencies using pip:
```bash
pip install scrapy sentence-transformers numpy faiss-cpu openai
