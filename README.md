# Medical Chatbot using RAG

## Overview
This project develops a Retrieval-Augmented Generation (RAG) based medical chatbot that answers healthcare-related questions using the Merck Manual as the knowledge base. The system retrieves relevant medical information and generates accurate, evidence-based responses using the LLaMA-2 language model.

## Features
- Medical question answering
- Retrieval-Augmented Generation (RAG)
- Vector embeddings for semantic search
- LLaMA-2 for response generation
- Response evaluation using Groundedness and Relevance

## Technologies Used
- Python
- LangChain
- ChromaDB
- LLaMA-2
- Hugging Face
- PyMuPDF

## Workflow
1. Load the Merck Manual PDF.
2. Split the document into text chunks.
3. Generate vector embeddings.
4. Store embeddings in ChromaDB.
5. Retrieve relevant chunks based on the user's question.
6. Generate an answer using LLaMA-2.
7. Evaluate the response using Groundedness and Relevance.

## Dataset
- Merck Manual of Diagnosis and Therapy (Medical PDF)

## Results
The RAG-based system generates more accurate and context-aware medical responses compared to prompt engineering alone.

## Conclusion
The project demonstrates how Retrieval-Augmented Generation improves the reliability and accuracy of medical question answering by combining document retrieval with a Large Language Model.

## Author
Jessima Afrin M
