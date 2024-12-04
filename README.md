# Question-and-answer-using-Langchain-and-Streamlit
Streamlit ChatGPT Integration

This repository contains a Streamlit application that integrates with ChatGPT via the LangChain library to provide a custom chatbot experience. Users can interact with ChatGPT, which is customized via system roles and user messages, creating a dynamic conversation environment.

Features

Interactive Chat Interface: Allows users to send messages and receive responses from ChatGPT.
Custom System Role: Set a system role for the chatbot which can influence the type of responses generated.
Environment-based Configuration: Utilizes a .env file to securely load the OpenAI API key.
Session State Management: Maintains chat history within Streamlit's session state for persistent interaction during the session.
Technologies

Streamlit: An open-source app framework for Machine Learning and Data Science projects.
LangChain: A library that facilitates the integration of language models like ChatGPT into applications.
dotenv: Manages environment variables from a .env file.
streamlit_chat: A Streamlit component for creating chat interfaces.
Installation

Prerequisites
Python 3.6+
Pip
Setup Environment
Clone the repository and set up a Python virtual environment:

# Clone the repository
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
Environment Configuration
Create a .env file in the root of your project directory and add your OpenAI API key:

OPENAI_API_KEY="sk-********"
Ensure this key is kept secure and not exposed publicly.

Usage

To run the application, execute the following command:

streamlit run ./project_streamlit_custom_chatgpt.py
Navigate to http://localhost:8501 in your web browser to view and interact with the application.

Application Structure

Sidebar Input: Users can set the system role and send new messages to the chatbot through the sidebar input fields.
Chat Display: Messages are displayed in a conversational format, with alternating positions to distinguish between the user and the chatbot.
Contributing

Contributions are welcome! Please fork the project, make your changes, and submit a pull request.

