# Retrieval-Augmented Generation (RAG) Application

This project demonstrates a Retrieval-Augmented Generation (RAG) pipeline, integrating document retrieval, embeddings, and question-answering using a combination of LangChain, Sentence Transformers, FAISS, and Google Gemini AI.

## Features
- Load markdown documents from a GitHub repository.
- Split documents into manageable chunks using `SpacyTextSplitter` or `RecursiveCharacterTextSplitter`.
- Create semantic embeddings with Sentence Transformers.
- Store and retrieve embeddings using FAISS for efficient document search.
- Integrate with Google Gemini AI for language model responses.
- Use a Retrieval-Augmented Generation (RAG) approach to answer questions based on retrieved document content.

## Requirements

Ensure you have the following libraries installed:

```bash
pip install --upgrade langchain langchain_community langchain-google-genai faiss-cpu sentence-transformers
pip install spacy
python -m spacy download en_core_web_sm
