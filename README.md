# LLM_Project-Book_Recommendations-

# Book Recommendation System using LLM

# Description

This project uses Large Language Models (LLMs) and semantic search to build a personalized book recommendation system that understands natural language queries and returns context-aware book suggestions.

# Features

- Personalized Book Recommendations: Understands user inputs like "I want a mystery novel like Sherlock Holmes" and returns relevant titles.
- LLM + LangChain: Uses OpenAI’s GPT model via LangChain to parse user intent and enhance natural language interaction.
- Semantic Search: Leverages Pinecone vector database to store and retrieve book embeddings based on similarity.
- User Interface: Built with Streamlit to allow real-time, interactive recommendations.

# Dataset Used

- Source: Kaggle - 7k Books with Metadata
- Attributes: Title, Author, Genre, Summary, Ratings, etc.

# Tech Stack

- Programming Language: Python
- LLM Framework: OpenAI API, LangChain
- Vector Store: Chroma
- Web App: Streamlit
- Libraries: pandas, numpy, Hugging Face Transformers, sentence-transformers

# How to Run

- Clone this repository
- git clone https://github.com/yourusername/book-recommendation-llm.git
- install all Requirement using pip
- run python "filename.py"


# Example Use Case

- Input: “I like historical fiction similar to The Book Thief.”
- Output: Returns a curated list of books from the dataset with similar themes, genres, and tone.
