# QA BOT USING WatsonX AI

## Overview

This project is a Question-Answering (QA) Bot powered by IBM WatsonX AI, LangChain, and ChromaDB. It allows users to upload PDF documents and query them using LLMs (Large Language Models) from IBM WatsonX AI. The bot processes user queries by retrieving relevant document segments and generating responses using AI models.

A Gradio web interface is implemented to enable seamless user interaction.

## Features

✅ Leverages IBM WatsonX AI for text embedding and retrieval.--
✅ Uses LangChain for document loading, text chunking, and retrieval-based QA.\n
✅ Integrates ChromaDB for vector storage and similarity search.\n
✅ Supports PDF document uploads for knowledge extraction.\n
✅ Gradio-powered web UI for easy interaction.\n
✅ Automatic installation of required dependencies.\n

## How It Works:

1️⃣ Upload a PDF document through the web interface.\n
2️⃣ The bot extracts text from the document and processes it into chunks.\n
3️⃣ ChromaDB stores the vector embeddings for efficient retrieval.\n
4️⃣ When a user asks a question, the system retrieves the most relevant text segments.\n
5️⃣ IBM WatsonX AI generates a response based on the retrieved information.\n

## Technologies Used

🔹 IBM WatsonX AI – for embedding and answering questions.\n
🔹 LangChain – for text processing and retrieval.\n
🔹 ChromaDB – for storing vector embeddings.\n
🔹 pypdf – for extracting text from PDFs.\n
🔹 Gradio – for building the web interface.\n

## The final result

<img width="1254" height="836" alt="1" src="https://github.com/user-attachments/assets/d7fbc2b9-3bbb-411e-b619-a697c6d3c732" />

