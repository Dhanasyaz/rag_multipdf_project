AI-Powered Multi-PDF Search Assistant (RAG)

Tech: Python, Streamlit, FAISS, EURI Embeddings API, GPT-4.1-nano, pdfplumber

Summary:
Built a simple AI tool that lets users upload multiple PDFs and ask questions about them. The system breaks the documents into small chunks, creates vector embeddings, stores them in a FAISS index, and retrieves the most relevant parts when a user asks a question. The final answer is generated using an LLM, based only on the retrieved content.

Key Features:

Extracts text from PDFs automatically

Splits large text into manageable chunks

Creates embeddings and stores them in a FAISS vector index

Retrieves the top relevant chunks for any question

Uses an LLM to generate clear, context-based answers

Clean Streamlit UI with chunk view and vector visualization
