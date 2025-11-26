
AI-Powered Multi-PDF Search Assistant (RAG)
A Retrieval-Augmented Generation (RAG) application that enables intelligent question-answering across multiple PDF documents using semantic search and large language models.

🔧 Tech Stack

Python - Core programming language
Streamlit - Interactive web interface
FAISS - Vector database for similarity search
EURI Embeddings API - Text-to-vector conversion
GPT-4.1-nano - Answer generation
pdfplumber - PDF text extraction

📋 Overview
This application allows users to upload multiple PDF files and ask natural language questions about their content. The system uses advanced RAG techniques to:

Extract and process text from uploaded PDFs
Split documents into semantic chunks
Generate vector embeddings for each chunk
Store embeddings in a FAISS vector database
Retrieve the most relevant chunks based on user queries
Generate accurate, context-aware answers using an LLM
Conversation memory remembers your chat history for natural follow-up questions


How to Run

Clone this repository
Install required packages:

bash   pip install streamlit faiss-cpu pdfplumber requests numpy

Run the app:

bash   streamlit run app.py

Open the link in your browser and start uploading PDFs

How it Works
The app reads your PDFs, breaks them into smaller pieces, and stores them in a way that makes searching fast. When you ask a question, it finds the most relevant pieces and uses AI to write an answer based on what it found.
Note
You'll need API keys for EURI Embeddings and GPT-4.1-nano, but you can use any similar API that works for your needs. Add your keys in the app before using.
