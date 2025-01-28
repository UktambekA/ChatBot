# Kitob Chatbot 🤖📖
🌟 Welcome to Your AI Book Companion!

## Overview
Kitob Chatbot is an interactive AI-powered application that allows users to engage with PDF books through question-answering, test generation, and summary extraction.

## Features
- PDF text extraction
- Context-based question answering
- Test generation from book content
- Summary creation
- Question-answer history tracking
- PDF export of conversation history

## Prerequisites
- Python 3.8+
- OpenAI API Key

## Installation
1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the Streamlit application:
```bash
streamlit run streamlit_app.py
```
2. Enter your OpenAI API key
3. Upload a PDF book
4. Interact with the chatbot by asking questions or requesting tests/summaries

## Components
- `streamlit_app.py`: Main Streamlit interface
- `book_chatbot.py`: Core chatbot logic
- `utils.py`: Utility functions for PDF handling

## Technologies
- Streamlit
- LangChain
- OpenAI GPT Models
- FAISS Vector Store
- PyPDF2

## Supported Languages
Currently optimized for Uzbek language interactions

## Limitations
- Requires internet connection
- Depends on OpenAI API
- Performance varies with book complexity

## Usage
https://chatbot1-pddetvez8akeg4odshlmke.streamlit.app/

