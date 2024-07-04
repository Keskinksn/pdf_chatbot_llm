# 🤖 PDF Chatbot

This Streamlit-based chatbot application allows users to upload PDF files, extract text from them, and ask questions based on the content of the PDFs. It provides detailed answers using Google Generative AI.

## 🚀 Features

- **PDF Reading and Text Extraction:** Upload multiple PDF files and extract the combined text.
- **Text Chunking:** Split the extracted text into manageable chunks for processing.
- **Vector Store Creation:** Create and save a FAISS vector store from the text chunks.
- **Question-Answering Chain:** Generate answers to user questions based on the context extracted from the PDFs using Google Generative AI.
- **Interactive Chat Interface:** Chat with the bot, upload PDFs, and clear chat history through a user-friendly Streamlit interface.

## 🛠️ Installation

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

env
Kodu kopyala
GOOGLE_API_KEY=your-google-api-key
📚 Usage
Run the Streamlit application:

bash
Kodu kopyala
streamlit run main.py
In the Streamlit interface:

Upload your PDF files using the sidebar uploader.
Click "Submit & Process" to extract and process the text.
Ask questions based on the content of the uploaded PDFs.
Clear chat history using the "Clear Chat History" button.
📂 Code Overview
Functions
get_pdf_text(pdf_docs): Reads all PDF files and returns the extracted text.
get_text_chunks(text): Splits the extracted text into chunks.
get_vector_store(chunks): Creates and saves a FAISS vector store from text chunks.
get_conversational_chain(): Sets up a conversational chain using Google Generative AI.
clear_chat_history(): Clears the chat history in the Streamlit session state.
user_input(user_question): Processes the user question, searches for similar documents, and returns the response from the conversational chain.
Streamlit Interface
Sidebar: For uploading PDF files and processing them.
Main Area: For displaying chat messages and interacting with the chatbot.
🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

📝 License
This project is licensed under the MIT License.

📧 Contact
For any questions or inquiries, please contact your-email@example.com.

arduino
Kodu kopyala

Bu düzenleme, metin içindeki kod parçalarının daha belirgin ve doğru formatta görünmesini sağlar. İhtiyaçlarınıza göre özelleştirebilirsiniz.
bash
pip install -r requirements.txt bu kısım doğru yapılmış sonuna bir şey yazmak gerekiyor mu bittiğine dair
ChatGPT
Kod bloklarının sonuna herhangi bir şey yazmanıza gerek yoktur. Ancak, daha açıklayıcı olması için her adımın sonunda neler yapılacağını belirten açıklamalar ekleyebilirsiniz. İşte kod bloklarının daha açıklayıcı bir şekilde düzenlenmiş hali:

markdown
Kodu kopyala
# 🤖 PDF Chatbot

This Streamlit-based chatbot application allows users to upload PDF files, extract text from them, and ask questions based on the content of the PDFs. It provides detailed answers using Google Generative AI.

## 🚀 Features

- **PDF Reading and Text Extraction:** Upload multiple PDF files and extract the combined text.
- **Text Chunking:** Split the extracted text into manageable chunks for processing.
- **Vector Store Creation:** Create and save a FAISS vector store from the text chunks.
- **Question-Answering Chain:** Generate answers to user questions based on the context extracted from the PDFs using Google Generative AI.
- **Interactive Chat Interface:** Chat with the bot, upload PDFs, and clear chat history through a user-friendly Streamlit interface.

## 🛠️ Installation

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

   ```sh
GOOGLE_API_KEY=your-google-api-key
```

📚 Usage
Run the Streamlit application:

bash
Kodu kopyala
streamlit run main.py
In the Streamlit interface:

Upload your PDF files using the sidebar uploader.
Click "Submit & Process" to extract and process the text.
Ask questions based on the content of the uploaded PDFs.
Clear chat history using the "Clear Chat History" button.
📂 Code Overview
Functions
get_pdf_text(pdf_docs): Reads all PDF files and returns the extracted text.
get_text_chunks(text): Splits the extracted text into chunks.
get_vector_store(chunks): Creates and saves a FAISS vector store from text chunks.
get_conversational_chain(): Sets up a conversational chain using Google Generative AI.
clear_chat_history(): Clears the chat history in the Streamlit session state.
user_input(user_question): Processes the user question, searches for similar documents, and returns the response from the conversational chain.
