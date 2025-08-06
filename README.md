# NCERT_QA_System

A semantic search-based Question Answering (QA) system built using NCERT textbook data. The system leverages sentence embeddings and vector similarity search to provide relevant answers to user queries based on content from class 12th NCERT books (Physics, Chemistry, and Computer Science).

## Features

- Semantic search using sentence-transformers
- Fast retrieval using FAISS indexing
- Automatic extraction and preprocessing of textbook content from PDFs
- Chunking strategy for better context representation
- Embedding storage and question-answer dataset generation

## Folder Structure

NCERT_QA_System/
├── pdfs/ # NCERT textbooks in PDF format
├── DatasetQA.csv # Extracted QA pairs (large file)
├── chunk_data.pkl # Chunked context data
├── question_embeddings.pkl # Precomputed sentence embeddings (large file)
├── ncert_index/ # FAISS vector index
├── ncert_qa_colab.ipynb # Jupyter notebook for building and testing the QA system
├── README.md # Project documentation

