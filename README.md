# Floatchat – AI Ocean Data Chatbot

## Description

Floatchat is an AI-powered chatbot designed to provide insights from real-world ocean datasets, including data related to salinity, temperature, and marine conditions.
It uses Retrieval-Augmented Generation (RAG) to deliver context-aware and accurate responses based on large-scale data.

## Features

* Chat-based interface for querying ocean data
* Data cleaning and preprocessing of large, unstructured datasets
* Context-aware responses using Retrieval-Augmented Generation (RAG)
* Integration of Large Language Model (LLM) for intelligent answers
* Backend system for efficient data storage and retrieval

## Tech Stack

* Python
* PostgreSQL
* RAG (Retrieval-Augmented Generation)
* LLM (Ollama)
* Vector Database

## How It Works

1. Collected large-scale ocean datasets (Arabian Sea, Bay of Bengal, Indian Ocean)
2. Cleaned and structured raw data for processing
3. Stored processed data in PostgreSQL and vector database
4. Implemented RAG pipeline to retrieve relevant data based on user queries
5. Used Ollama (LLM) to generate context-aware responses

## Architecture

User Query → Retrieval (Vector DB) → Context Injection → LLM (Ollama) → Response

## Future Improvements

* Improve response accuracy and latency
* Expand dataset coverage
* Enhance frontend interface

