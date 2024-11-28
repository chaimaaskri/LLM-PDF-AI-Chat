# LLM-PDF-AI-Chat

Welcome to **LLM-PDF-AI-Chat**! 🚀 This application allows users to interact with the content of PDF files conversationally using cutting-edge language models and vector search.  


## Overview

This project combines **Google Gemini's Generative AI**, **LangChain**, and **FAISS** to extract and process PDF content, enabling users to ask detailed questions and receive precise answers based on the context of the documents.

## Features

- **PDF Text Extraction**: Process multiple PDFs and extract text for analysis.
- **Conversational AI**: Use advanced AI models to answer questions about your PDFs.
- **Embeddings and Vector Search**: Efficient text similarity search using Google Generative AI embeddings and FAISS.
- **User-Friendly Interface**: A clean and intuitive Streamlit app for easy interaction.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Python 3.9 or later
- A valid Google Generative AI API key

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/LLM-PDF-AI-Chat.git
   cd LLM-PDF-AI-Chat
 
 2. **Set Up a Virtual Environment** :
 ```
bash
Copier le code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
 ```
 3. **Install Dependencies**:

 ```bash
Copier le code
pip install -r requirements.txt
 ```
4.  **Add Your API Key**:
 ```
Create a .env file in the project directory and add your Google API key:
 ```
 ```env
Copier le code
GOOGLE_API_KEY=your_google_api_key
Run the App:
 ```
 ```bash
Copier le code
streamlit run app.py
 ```
## Usage
 ```
Upload your PDF files in the sidebar.
Click on Submit & Process to extract and index the content.
Ask questions in the input box, and the AI will respond with context-based answers.
Example Queries
"Summarize the key findings of the report."
"What are the challenges mentioned in the document?"
"Is there any mention of climate policies in the text?"
 ```
## File Structure
 ```
plaintext
Copier le code
.
├── app1.py                # Main application file
├── requirements.txt      # List of dependencies
├── .env                  # API keys and environment variables
└── README.md             # Documentation
 ```


## Author

👩‍💻 Chaima Askri
📅 Version 1.0

Feel free to contribute, report issues, or suggest improvements. Happy chatting with your PDFs! ✨
