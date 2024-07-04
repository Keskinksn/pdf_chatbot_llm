# PDF Chatbot 


This project is a Streamlit-based chatbot application that allows users to upload PDF files, extract text from them, and ask questions based on the content of the PDFs. The chatbot utilizes Google Generative AI to provide detailed answers.

## Features

- **PDF Reading and Text Extraction:** Upload multiple PDF files and extract the combined text.
- **Text Chunking:** Split the extracted text into manageable chunks for processing.
- **Vector Store Creation:** Create a FAISS vector store from the text chunks and save it locally.
- **Question-Answering Chain:** Generate answers to user questions based on the context extracted from the PDFs using Google Generative AI.
- **Interactive Chat Interface:** Chat with the bot, upload PDFs, and clear chat history through a user-friendly Streamlit interface.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pdf-chatbot.git
   cd pdf-chatbot
Install the required packages:

bash
Kodu kopyala
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the project root directory and add your Google API key:

makefile
Kodu kopyala
GOOGLE_API_KEY=your-google-api-key
Usage
Run the Streamlit application:

bash
Kodu kopyala
streamlit run main.py
In the Streamlit interface:

Upload your PDF files using the sidebar uploader.
Click "Submit & Process" to extract and process the text.
Ask questions based on the content of the uploaded PDFs.
Clear chat history using the "Clear Chat History" button.

Streamlit Interface
Sidebar: For uploading PDF files and processing them.
Main Area: For displaying chat messages and interacting with the chatbot
