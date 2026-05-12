# Implementation of the TF-IDF and Cosine Similarity Methods in Telegram Bots to Support Laptop Recommendations Based on User Preferences 

TF-IDF & Cosine Similarity powered Telegram Bot
<p align="center"> <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python"> <img src="https://img.shields.io/badge/NLP-TF--IDF-green"> <img src="https://img.shields.io/badge/Similarity-Cosine-orange"> <img src="https://img.shields.io/badge/Platform-Telegram-blue?logo=telegram"> <img src="https://img.shields.io/badge/Status-Completed-success"> <img src="https://img.shields.io/badge/Accuracy-80%25-brightgreen"> </p>

-Overview

This project is a Laptop Recommendation System implemented as a Telegram chatbot using Natural Language Processing techniques.

It leverages:

TF-IDF → to represent user queries and laptop specifications
Cosine Similarity → to find the most relevant laptop

The system achieves 80% accuracy in answering user queries.

-Key Features
1. Telegram-based chatbot interface
2. Smart laptop recommendation based on user queries
3. NLP-powered similarity matching
4. Fast and lightweight implementation
5. Fallback response for unknown queries

-Tools & Technologies

Python, Pandas, Scikit-learn, NLTK, Telegram Bot API

-How It Works

![Pickup by Hour](Conceptual_Framework.png)

-Dataset

Source: Kaggle

https://www.kaggle.com/code/markmedhat/laptop-price-data-analysis/comments#2838660-

Total Records: 1303 laptops

![Pickup by Hour](Dataset.png)

-Methods

1. TF-IDF

Used to assign weights to words based on their frequency and importance in documents.

2. Cosine Similarity

Used to measure similarity between:

User query, Laptop data

Similarity score:

Close to 1 → highly similar, Close to 0 → not similar

-Workflow

1. User inputs a query
2. Text preprocessing (tokenization & normalization)
3. TF-IDF vectorization
4. Compute Cosine Similarity
5. Retrieve top matching laptops

-Chatbot Implementation

Built using:

1. Python
2. Telegram Bot API
3. BotFather (for API token)

Features:

1. Responds to user queries
2. Provides laptop recommendations
3. Handles unknown queries with fallback responses

-Evaluation

Testing was conducted using:

10 sample queries

Results:

8 correct responses

2 incorrect responses

Return recommendation via chatbot

![Pickup by Hour](Chatbot1.png)

![Pickup by Hour](Chatbot2.png)
