# AI AGENT DOCUMENT PROCESSING WITH LANGCHAIN

This project demonstrates how to process, chunk, and index documents using LangChain to build a vector store for retrieving information about AI agents. It supports multiple document types like text, web pages, and PDFs, and uses OpenAI embeddings for similarity search.

## FEATURES

- Load documents from:
  - Text files
  - Web pages
  - PDF files
- Process documents by chunking with customizable size and overlap.
- Index documents in a vector store using OpenAI embeddings.
- Perform a similarity search to retrieve the most relevant documents for a query.

## REQUIREMENTS

- Python 3.7+
- Libraries:
  - `langchain-community`
  - `dotenv`
  - `bs4`
  - `chromadb`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aditya10avg/RAG-Pipeline---LangChain-.git
   cd RAG-Pipeline---LangChain-
   ```
2. Create a virtual environment and activate it:

  ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
  ```
3. Install dependencies
   ```bash
      pip install -r requirements.txt
   ```
4. Set up your .env file.
  ```bash
    OPEN_AI_API_KEY=your_openai_api_key
  ```
## USAGE
#### 1. SCRAPPING WEB PAGE FOR Q&A
#### 2. PDF Q&A

## TECH STACKS USED
#### 1. OPENAI EMBEDDINGS
#### 2. LANGCHAIN
#### 3. BEAUTIFUL SOUP
#### 4. CHROMA DB

## RAG WORKFLOW FOR DOCUMENT PROCESSING AND CREATING A Q&A WITH ITS VECTORE STORAGE

![image](https://github.com/user-attachments/assets/1c4310a9-cf9a-406c-9d2b-25d9239d8dc5)
