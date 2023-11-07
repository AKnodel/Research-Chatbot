# Research ChatBot: News Research Tool 📈

![Research ChatBot](./Research_Chatbot.jpg)

This Research ChatBot is an innovative web application designed to address two crucial challenges in the realm of AI-powered chat systems. Firstly, unlike traditional chat systems such as ChatGPT, this chatbot is engineered to work with updated and real-time data, ensuring the provision of the most current information. Secondly, it offers a solution to the word limit constraints that typically restrict the amount of data that can be processed in chat interfaces, making it a versatile tool for handling extensive text data. Developed using Python, Streamlit, and Langchain, this ChatBot empowers users to process news article URLs, perform text splitting, create embeddings, and seamlessly find answers to questions about the content within the articles.

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

This project is powered by Langchain and leverages natural language processing and machine learning techniques. To learn more about Langchain, visit the [Langchain website](https://langchain.com).

