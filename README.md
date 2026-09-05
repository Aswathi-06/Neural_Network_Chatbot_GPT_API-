# Neural Network Chatbot — Powered by GPT API

Neural Network Chatbot is a Python-based chatbot application built using OpenAI's GPT API. The project uses a GPT transformer neural network to generate responses based on the user's messages and previous conversation history. GPT models are neural networks that are trained to predict the next token in a sequence and can generate human-like responses based on the given context.

In this project, the OpenAI Python SDK is used to connect the Python program with the GPT API. A custom `ChatBot` class is created to manage the chatbot's conversation history, send user messages to the API, receive responses, and track the total number of tokens used during the session. The chatbot also includes error handling and automatic retries for rate-limit errors.

The project provides two ways to interact with the chatbot. The first is a simple text-based chat loop that runs directly in the notebook, where the user can type messages and receive responses. The second is an optional web-based chat interface built using Gradio, which provides a more user-friendly chat window and can generate a shareable link for demonstration.

The chatbot also includes features such as resetting the conversation memory, tracking token usage, and maintaining context throughout a session. The project can be further extended with custom chatbot personas, streaming responses, Retrieval-Augmented Generation (RAG), voice interaction, and persistent conversation storage.
