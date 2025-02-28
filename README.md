# Mental Health Chatbot

This is a Streamlit application that allows users to upload PDF files and interact with a mental health chatbot powered by a language model.

## Requirements

To run this application, you need to install the following dependencies:

- Python 3.7 or higher
- Streamlit
- Langchain
- Langchain-Groq
- Hugging Face Hub

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your API key for the ChatGroq model. It is recommended to use environment variables or a configuration file to manage sensitive information.

## Running the Application

To run the application, use the following command:
```bash
streamlit run app.py
```

Open your browser and navigate to `http://localhost:8501` to access the application.

## Usage

1. Upload your PDF files using the file uploader.
2. Click on "Process PDFs" to create a vector database.
3. Ask your questions in the text input field and click "Get Answer" to receive responses from the chatbot.

## Note

Make sure to handle your API key securely and do not hardcode it in the application.
