# Structured-RAG-PDF

This project explores the extraction of structured information from PDF documents using Langchain and OpenAI models.

---

## Key Features
- **PDF Parsing:** Efficiently extracts text from PDF documents.
- **Information Extraction:** Utilizes Langchain's capabilities to identify and extract key-value pairs, lists, tables, and other structured data from the extracted text.
- **RAG Integration:** Leverages OpenAI models (e.g., GPT-3.5, GPT-4) within a Retrieval Augmented Generation (RAG) framework to enhance information extraction accuracy and provide more comprehensive insights.
- **Customizable:** Allows for customization of extraction rules, data structures, and the underlying language models to adapt to specific document types and information needs.

---

## Project Structure
- **`pdf_parser.py`:** Contains functions for parsing PDF documents and extracting raw text.
- **`information_extractor.py`:** Implements logic for identifying and extracting structured information from the extracted text using regular expressions, NLP techniques, and Langchain's built-in capabilities.
- **`rag_pipeline.py`:** Defines the RAG pipeline, including document loading, text extraction, embedding generation, vector database storage, and query-driven information retrieval.
- **`model_interaction.py`:** Handles interactions with OpenAI models for tasks like question answering, summarization, and generating insights based on the extracted information.
- **`utils.py`:** Contains helper functions for common tasks, such as loading configurations, handling file I/O, and formatting output.

---

## Setup and Usage

### 1. Install Dependencies
Make sure you have Python 3.8+ installed. Install the required dependencies using:
```bash
pip install -r requirements.txt

