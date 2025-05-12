# YouTube-Chatbot-using-LangChain-

This project implements a YouTube video chatbot that allows users to ask questions about the content of a specific YouTube video. It retrieves the video transcript, processes it, and uses LangChain to generate relevant responses based on the provided context. The objective is to create an interactive interface for users to query video content effectively.

## Features
- Extracts transcripts from YouTube videos.
- Splits transcripts into manageable text chunks.
- Embeds text using OpenAI embeddings.
- Stores embeddings in a FAISS vector store.
- Retrieves relevant context based on user queries.
- Generates AI-powered responses using LangChain and GPT models.

## Tech Stack & Libraries
- Python
- LangChain
- OpenAI API
- FAISS
- YouTube Transcript API
- dotenv
- tiktoken
