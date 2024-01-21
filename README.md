# chatbot_ecommerce

E-commerce Chatbot

Overview:<br>
This repository contains a comprehensive system for recommending fashion products, specifically focusing on blue jeans. It utilizes advanced machine learning and natural language processing techniques to provide relevant fashion recommendations based on user input.

Features:<br>
Image and Text Analysis: Integrates Sentence Transformers for encoding product images and descriptions, enabling semantic search capabilities.<br>
Fashion Product Dataset: Utilizes the ashraq/fashion-product-images-small dataset from Hugging Face's dataset library.<br>
User-Friendly Query Interface: Accepts user input for specific fashion items (e.g., "blue jeans") and returns a list of top-recommended products.<br>
Semantic Search: Employs semantic search to find the most relevant products based on image and text embeddings.<br>
Customizable Response Templates: Uses langchain and PromptTemplate to generate user-friendly responses detailing product features like season, usage, and type.<br>

Tech Stack:<br>
datasets: For loading and handling the fashion product dataset.<br>
sentence_transformers: For generating embeddings of product images and descriptions.<br>
langchain: Provides the framework for constructing conversational AI and handling response generation.<br>
openai: Utilized for GPT-3.5-Turbo models to power conversational AI capabilities.<br>
Python standard libraries: os, json, etc., for basic operations.<br>

How It Works:<br>
Data Preparation: Loads fashion product data and processes it into a structured format.<br>
Embedding Generation: Creates embeddings for both product images and text descriptions.<br>
Query Handling: Accepts user queries and finds relevant products using semantic search.<br>
Response Generation: Generates informative and user-friendly product descriptions and recommendations based on the query.<br>

