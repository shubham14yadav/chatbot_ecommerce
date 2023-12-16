# chatbot_ecommerce

Fashion Chatbot

Overview
This repository contains a comprehensive system for recommending fashion products, specifically focusing on blue jeans. It utilizes advanced machine learning and natural language processing techniques to provide relevant fashion recommendations based on user input.

Features
Image and Text Analysis: Integrates Sentence Transformers for encoding product images and descriptions, enabling semantic search capabilities.
Fashion Product Dataset: Utilizes the ashraq/fashion-product-images-small dataset from Hugging Face's dataset library.
User-Friendly Query Interface: Accepts user input for specific fashion items (e.g., "blue jeans") and returns a list of top-recommended products.
Semantic Search: Employs semantic search to find the most relevant products based on image and text embeddings.
Customizable Response Templates: Uses langchain and PromptTemplate to generate user-friendly responses detailing product features like season, usage, and type.

Tech Stack
datasets: For loading and handling the fashion product dataset.
sentence_transformers: For generating embeddings of product images and descriptions.
langchain: Provides the framework for constructing conversational AI and handling response generation.
openai: Utilized for GPT-3.5-Turbo models to power conversational AI capabilities.
Python standard libraries: os, json, etc., for basic operations.

How It Works
Data Preparation: Loads fashion product data and processes it into a structured format.
Embedding Generation: Creates embeddings for both product images and text descriptions.
Query Handling: Accepts user queries and finds relevant products using semantic search.
Response Generation: Generates informative and user-friendly product descriptions and recommendations based on the query.

