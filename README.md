# Chatbot LLM Project

Welcome to the Chatbot LLM project! This chatbot leverages the power of Pinecone vector databases, the language capabilities of GPT-3.5, and Langchain for learning and adapting to provide intelligent responses to user questions. The Streamlit framework is used for creating the user interface.

## Project Overview

This project combines several powerful technologies to create a chatbot that learns from data stored in Pinecone vector databases, utilizes GPT-3.5 to generate responses, and employs Langchain for learning and improving over time. Here's an overview of the components:

- **Streamlit**: A web application framework for creating interactive and user-friendly interfaces, Streamlit serves as the front end of our chatbot. It allows users to interact with the chatbot via a web browser.

- **Pinecone**: A vector database that stores and retrieves vector embeddings efficiently. Pinecone is used to manage and query the vector representations of data, making it possible for the chatbot to learn from a large dataset.

- **GPT-3.5**: A state-of-the-art language model by OpenAI, GPT-3.5 is responsible for generating human-like responses to user queries. It can answer questions, provide information, and engage in natural language conversations.

- **Langchain**: Langchain is an integral part of the project, serving as the learning component for the chatbot. It helps the chatbot adapt and improve its responses over time, ensuring that it becomes more intelligent and context-aware with each interaction.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:

    `git clone https://github.com/your-username/chatbot-llm.git`

    `cd chatbot-llm`

2. **Environment Setup**:
- Create a virtual environment and activate it.
- Install the required dependencies listed in `requirements.txt`.
- Set up your Pinecone account and provide the necessary API keys.

3. **Running the Application**:
- Use Streamlit to run the application:
  ```
  streamlit run app.py
  ```
- Access the chatbot interface via your web browser.

4. **Interact with the Chatbot**:
- Start interacting with the chatbot by asking questions or engaging in conversations.
