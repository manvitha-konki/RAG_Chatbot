# RAG Chatbot 🤖

This project implements a Retrieval-Augmented Generation (RAG) chatbot that combines a Large Language Model (LLM) with a retrieval mechanism to provide more accurate and context-aware answers.

Instead of depending only on the LLM’s pre-trained knowledge, the chatbot retrieves relevant information from a local knowledge base and uses it to generate responses.

## Features

**Retrieve Answers from Documents:**  Get precise answers directly from your own PDFs, text files, or other documents.

**Plug-and-Play Knowledge Base:**  Easily add documents to your knowledge base without complicated setup.

**LLM Integration (Gemini):** Leverages Gemini for advanced language understanding and response generation.

**Efficient Search with Embeddings:**  Uses embeddings combined with a vector database for fast and relevant information retrieval.

**Modular Pipeline:** Built with a retriever + generator architecture for flexibility and scalability.

## Tech Stack

**Backend:** Python, FastAPI

**Frontend:** Streamlit

**Embeddings:** Google GenAI

**Vector Store:** ChromaDB

**Document Processing:** LangChain, Unstructured

