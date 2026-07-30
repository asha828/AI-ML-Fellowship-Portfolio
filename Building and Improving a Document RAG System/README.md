# Document RAG Customer Support Assistant

## Overview

Developed a Retrieval-Augmented Generation (RAG) application using LangChain and OpenAI to power a customer support assistant for a fictional outdoor gear company. The system retrieves relevant information from a company knowledge base and generates responses to customer questions while minimizing hallucinations.

## Features

- Loaded and processed an unstructured customer support knowledge base
- Split documents into optimized text chunks using RecursiveCharacterTextSplitter
- Generated embeddings with OpenAI's `text-embedding-3-small` model
- Built a vector database using Chroma for semantic similarity search
- Created a Retrieval-Augmented Generation (RAG) pipeline with LangChain
- Engineered prompts to ensure responses remained grounded in retrieved context
- Implemented query rewriting to improve retrieval performance on short or ambiguous customer queries
- Evaluated retrieval quality and compared baseline versus rewritten-query performance

## Tech Stack

- Python
- LangChain
- OpenAI API
- Chroma Vector Database
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Prompt Engineering

## Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- Vector Embeddings
- Semantic Search
- Prompt Engineering
- Document Chunking
- Query Transformation
- LLM Application Development
- AI Pipeline Evaluation

## Results

Built an end-to-end RAG system capable of answering customer support questions using retrieved knowledge rather than model memory. Query rewriting improved the quality and professionalism of responses for ambiguous customer questions while demonstrating the tradeoff between retrieval accuracy and additional inference cost.
