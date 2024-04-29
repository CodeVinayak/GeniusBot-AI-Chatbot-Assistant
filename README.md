# GeniusBot: AI-Powered Assistance with PDF Insight

GeniusBot is a Streamlit-based chatbot application that leverages the power of OpenAI's GPT-3.5-turbo language model to provide intelligent assistance to users. This application is designed to help users gain insights from PDF documents by allowing them to upload a PDF file and ask questions related to its content. Additionally, GeniusBot can also answer simple questions without the need to upload a PDF.

## Features

- Upload and analyze PDF files
- Ask questions related to the uploaded PDF
- Receive contextual responses based on the PDF content
- Answer simple questions without the need for a PDF
- Interactive chat interface with conversation history
- Responsive design for mobile devices

## Technologies Used

### Frontend
- **Streamlit**: A Python library that enables the creation of interactive web applications with minimal effort.

### Backend
- **OpenAI GPT-3.5-turbo**: A powerful language model developed by OpenAI, capable of understanding and generating human-like text.
- **LangChain**: A framework for building applications with large language models (LLMs) like GPT-3.5-turbo.
- **PyPDF2**: A pure-python library built as a PDF toolkit for extracting text from PDF files.

### Development Tools
- **Python**: The primary programming language used for the project.
- **Streamlit**: Used for building the interactive user interface.
- **Git**: Version control system for managing the codebase.

## Project Structure
The project follows a modular structure with separate components for handling different functionalities:

1. **PDF Processing**: This module is responsible for extracting text from uploaded PDF files using the PyPDF2 library.
2. **OpenAI Integration**: This module handles the communication with the OpenAI GPT-3.5-turbo model, sending queries and receiving responses.
3. **User Interface**: The Streamlit library is used to create the interactive chat interface, allowing users to upload PDFs, ask questions, and receive responses from the AI assistant.
4. **State Management**: Streamlit's session state is utilized to maintain the conversation history and manage the application's state.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://openai.com/)
- [LangChain](https://python.langchain.com/)
- [PyPDF2](https://pythonhosted.org/PyPDF2/)