# 📄 Chat with PDF Using Google Gemini 🤖
This is a Streamlit web application that allows users to upload PDF files and ask questions based on the content of those PDFs. The application uses Google Gemini AI (Google Generative AI) for embedding and question-answering, PyPDF2 for extracting text from PDFs, and FAISS for vector database creation and similarity search. This combination enables a user to chat with the uploaded PDFs and retrieve contextually relevant answers.

## Features
PDF Upload and Text Extraction: Users can upload multiple PDFs, and the app extracts the text content using PyPDF2.

Text Chunking: The extracted text is divided into smaller chunks using RecursiveCharacterTextSplitter for more efficient processing.

Embeddings with Google Gemini AI: The application uses Google Gemini models to convert text into embeddings and store them in a vector database for semantic search.

Question-Answering: Users can ask questions based on the content of the uploaded PDFs, and the app generates relevant answers.

FAISS Vector Store: Utilizes FAISS to store and search through the embeddings for relevant chunks of text to answer user queries.

Streamlit Frontend: A clean, user-friendly interface for uploading PDFs and interacting with the app.

## Tech Stack
Frontend: Streamlit

Backend: Python, LangChain

Vector Database: FAISS

PDF Parsing: PyPDF2

Language Model: Google Gemini AI (Generative AI)

## Requirements
To run the application, you will need:

Python 3.8+

Google API Key for accessing Google Gemini AI (GOOGLE_API_KEY)

Dependencies listed in requirements.txt
