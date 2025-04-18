#It's a web scraping + RAG application built with Streamlit, LangChain, OpenAI, and Chroma

#This project is a Streamlit-based RAG (Retrieval-Augmented Generation) application that uses OpenAI's language models for intelligent Q&A.
#It begins by scraping content from specified website URLs using LangChain’s UnstructuredURLLoader.
#The scraped data is split, embedded, and stored in a Chroma vector database for fast semantic search.
#When a user enters a question, the system retrieves the most relevant content and generates a precise, contextual answer using OpenAI.
