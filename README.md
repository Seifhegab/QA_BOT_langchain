# QA BOT USING WatsonX AI

## Overview

This project is a Question-Answering (QA) Bot powered by IBM WatsonX AI, LangChain, and ChromaDB. It allows users to upload PDF documents and query them using LLMs (Large Language Models) from IBM WatsonX AI. The bot processes user queries by retrieving relevant document segments and generating responses using AI models.

A Gradio web interface is implemented to enable seamless user interaction.

## Features

✅ Leverages IBM WatsonX AI for text embedding and retrieval.
✅ Uses LangChain for document loading, text chunking, and retrieval-based QA.
✅ Integrates ChromaDB for vector storage and similarity search.
✅ Supports PDF document uploads for knowledge extraction.
✅ Gradio-powered web UI for easy interaction.
✅ Automatic installation of required dependencies.

## How It Works:

1️⃣ Upload a PDF document through the web interface.
2️⃣ The bot extracts text from the document and processes it into chunks.
3️⃣ ChromaDB stores the vector embeddings for efficient retrieval.
4️⃣ When a user asks a question, the system retrieves the most relevant text segments.
5️⃣ IBM WatsonX AI generates a response based on the retrieved information.

## Technologies Used

🔹 IBM WatsonX AI – for embedding and answering questions.
🔹 LangChain – for text processing and retrieval.
🔹 ChromaDB – for storing vector embeddings.
🔹 pypdf – for extracting text from PDFs.
🔹 Gradio – for building the web interface.
