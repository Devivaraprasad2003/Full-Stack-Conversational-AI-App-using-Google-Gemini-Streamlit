# Full-Stack-Conversational-AI-App-using-Google-Gemini-Streamlit
This project is a lightweight Conversational AI application built using Google Gemini (Generative AI) and Python. It includes both a Streamlit-based chatbot UI and a CLI chatbot, making it easy to run on the web or directly in the terminal.

The project demonstrates how to integrate LLM APIs, manage chat sessions, load environment variables securely, and build simple full-stack AI applications suitable for learning and portfolio use.

🌟 Features

Conversational AI powered by Gemini 2.0 Flash

Streamlit web interface for interactive chat

CLI version for terminal-based chat

Secure API key handling using .env

Chat session history support

Beginner-friendly, clean, and easy to extend

📁 Project Structure
project/
│── Gemini_Chat_Bot_UI.py       # Streamlit chatbot UI
│── gemini_chat_cli.py          # CLI chat application
│── requirements.txt
│── .env.example                # Example environment file
│── README.md

🔧 Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

2. Install dependencies
pip install -r requirements.txt

3. Add your Gemini API key

Create a .env file in the project folder:

Gemini_Api=YOUR_API_KEY_HERE


(Never upload your real API key to GitHub.)

🖥️ Running the Streamlit Web Chatbot
streamlit run Gemini_Chat_Bot_UI.py


This will open the application in your browser.

🧑‍💻 Running the CLI Chatbot
python gemini_chat_cli.py

CLI Commands:

/show → Display chat history

/save → Save history to chat_history.json

/exit or /quit → Quit the application

🎯 Use Cases

Learning how to work with Google Gemini API

Understanding LLM chat workflows

Building simple AI assistants

Academic or portfolio-ready AI projects

Quick prototyping for conversational systems

📦 Tech Stack

Python

Streamlit

Google Generative AI

python-dotenv

JSON (optional history saving)


