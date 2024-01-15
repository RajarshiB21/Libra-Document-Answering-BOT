# Libra-Document-Answering-BOT

## Interactive PDF Text Analyzer and QA System
A Python-based tool that extracts and processes text from PDFs, generates text embeddings, and offers an interactive question-answering interface using OpenAI models and `ipywidgets` for insightful text analysis.

### Overview
This project enables effective analysis and querying of text from PDF documents using Python libraries and OpenAI's models. It's designed to extract, process, and interact with text data for insightful analysis.

### Features
- **PDF Text Extraction**: Utilizes `PyPDF2` for extracting text from any PDF document.
- **Text Processing and Chunking**: Splits the extracted text into manageable chunks, preparing it for further processing.
- **Embedding Generation**: Converts text chunks into embeddings using OpenAI's advanced language models for efficient text analysis.
- **Interactive Question-Answering Interface**: Features a user-friendly interface built with `ipywidgets` for querying and displaying answers from the processed text.

### Installation
Instructions on how to install the required libraries.

```bash
pip install langchain openai PyPDF2 faiss-cpu tiktoken
