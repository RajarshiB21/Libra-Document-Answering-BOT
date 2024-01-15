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
```

### Usage
To use this tool, follow these steps:

1. **Open the Code File**: Open the Python script in your environment.
2. **Upload Your Document**: Upload the PDF document you want to analyze.
3. **Modify the Script for Your Document**:
   - Locate the line `pdfreader = PdfReader('YOUR PDF FILE HERE')`.
   - Replace `'YOUR PDF FILE HERE'` with the name of your uploaded PDF file. Ensure the file name is enclosed in quotes.
4. **Use the GUI**:
   - Scroll to the end of the code file where the GUI code is located.
   - Run the script. A text box and a submit button will appear in your Jupyter notebook interface.
   - Type your question into the text box and click the submit button to get an answer based on the content of your PDF.
