# Enhanced Q&A Chatbot With OpenAI

This project is a simple yet powerful Q&A chatbot built using OpenAI's models. It leverages the Streamlit framework for a user-friendly interface and allows seamless interaction with different OpenAI models like GPT-4.

## Features

- **OpenAI Integration**: Ask any question and get answers from OpenAI’s GPT models.
- **Model Selection**: Choose from various models such as `gpt-4`, `gpt-4-turbo`, and `gpt-4o`.
- **Adjustable Parameters**: Customize your chatbot’s responses by tweaking parameters like `temperature` and `max tokens`.
- **Interactive UI**: The chatbot is embedded in a web interface built with Streamlit, featuring adjustable settings in the sidebar for quick modifications.
- **Langchain Support**: This project utilizes Langchain for enhanced prompt handling and output parsing, along with Langsmith for tracing and tracking API performance.

## Requirements

- Python 3.10+
- Streamlit
- OpenAI API key
- Langchain and Lancgain API key
- dotenv

Set up your environment variables by creating a .env file:
   ```bash
       LANGCHAIN_API_KEY=your-langchain-api-key
   ```
Run the application:
   ```bash
       streamlit run app.py
   ```
