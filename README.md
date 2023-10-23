# Research ChatBot: News Research Tool 📈

![Research ChatBot](./Research_Chatbot.jpg)

This Research ChatBot is a web application that allows you to process news article URLs, split the text data, create embeddings, and answer questions about the content from those articles. It is designed using Python, Streamlit, and Langchain.

## Features

- **URL Processing**: Input up to three news article URLs for analysis.
- **Text Splitting**: The tool automatically splits text data into manageable chunks.
- **Embeddings**: Create embeddings using OpenAI's GPT-3 or another model from Hugging Face Transformers.
- **Question-Answering**: Ask questions about the content of the articles and receive answers with sources.

## Installation

1. Clone this repository.
2. Install the required packages by running `pip install -r requirements.txt`.
3. Create a `.env` file with your OpenAI API key.

## Usage

1. Start the app by running `streamlit run main.py`.
2. Input the URLs of the news articles you want to analyze.
3. Click the "Process URLs" button to begin the analysis.
4. Enter your questions in the input box and receive answers with sources.

## Dependencies

- Python
- Streamlit
- Langchain
- Hugging Face Transformers (for alternative model usage)

---

This project is powered by Langchain and leverages natural language processing and machine learning techniques. To learn more about Langchain, visit the [Langchain website](https://langchain.io).

