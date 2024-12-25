# LangChain-ChatBot-OpenSource
This is a simple demonstration of integrating LangChain with LLAMA2 using the Streamlit framework. The application takes a user query and generates a response using the LLAMA2 model.

## Features

- **LangChain Integration**: Implements a LangChain pipeline for handling prompt templates, LLM integration, and output parsing.
- **LLAMA2 Model**: Utilizes the Ollama implementation of the LLAMA2 model for generating AI responses.
- **Streamlit UI**: A lightweight web interface to input queries and view responses in real time.
- **Environment Variables**: Securely handles API keys using `.env` files.

## Prerequisites

- Python 3.8+
- A `.env` file containing the `LANGCHAIN_API_KEY` with a valid LangChain API key.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AkashR-16/LangChain-ChatBot-OpenSource.git

2. Create and activate a virtual environment:
   ```bash
    python -m venv venv
    venv\Scripts\activate
   
3. Install the required dependencies

4. Create a .env file and add your LangChain API key:
   ```bash
   LANGCHAIN_API_KEY=your_api_key_here

## Usage
1. Run the streamlit app
   ```bash
   streamlit run app.py
2. Open your browser and navigate to http://localhost:8501.
3. Enter a topic or question in the input box and get AI-generated responses.
