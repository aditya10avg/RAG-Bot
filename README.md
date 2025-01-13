# AI Agent Query System

This project uses Langchain and various language model tools to process documents, split them into chunks, embed them, and retrieve the most relevant answers to a given query. The AI Agent Query System leverages GPT-4 for generating step-by-step answers based on the context provided from document embeddings.

## Prerequisites

Before running the project, ensure you have the following installed:
- Python 3.12 or greater than 3.10
- pip
- [OpenAI API Key](https://beta.openai.com/signup/)

You also need to install the necessary libraries:
```bash
pip install langchain langchain-community python-dotenv Chroma openai
```
OR
```bash
pip install -r requirements.txt
```
This one is preferred.

## Project Setup
1. Load Environment Variables
Create a .env file in the root directory and add your OpenAI API key:
```bash
OPEN_AI_API_KEY=your_openai_api_key
```
2. Document Loading and Preprocessing
The system allows you to load a document (e.g., a PDF) and split it into smaller chunks for easier processing and better query responses.

3. Embedding and Vector Storage
The document chunks are embedded using the OpenAI API and stored in a Chroma vector store. This allows for similarity searches based on the content of the documents.

4. Retrieval and Query Response
A retriever is created to search for the most relevant document chunks based on a user query. The relevant context is then passed to GPT-4 for generating a detailed answer.

## How to Run
Prepare your PDF
You can place your document, e.g., ai_agents.pdf, in the project directory instead of the default pdf.

Run the notebooks to interact with the AI query system:

Input a Query
When prompted, you can just enter a question related to the document's content, and the system will generate a relevant answer.

### Notes:
- Replace `your_openai_api_key` with your actual OpenAI API key in the `.env` file.
- Make sure to adjust the Python notebook name and structure in the README if they differ from the provided example.

  ## FlowChart

  ![image](https://github.com/user-attachments/assets/708f8e11-d61e-4c9c-a5ef-08a46746a07d)
