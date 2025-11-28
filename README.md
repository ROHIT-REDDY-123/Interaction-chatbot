🤖 LangChain + Gemini Chat App

This is a simple Generative AI chat application built using LangChain, Google Gemini (2.5-Pro) and Streamlit.
The app allows users to ask any question, and the LLM responds instantly using Google's latest Gemini model.

📌 About the Project

This project demonstrates how to:

Connect LangChain with Google Gemini API

Build a reusable function to generate responses from Gemini

Create an interactive Q&A chat interface with Streamlit

Safely manage API keys using environment variables (.env)

Deploy a clean and functional AI chatbot using just a few lines of code

It serves as a beginner-friendly template for any Gemini-powered Streamlit application.

🛠 Features

✅ Clean and intuitive Streamlit UI
✅ Uses Gemini 2.5-Pro for high-quality responses
✅ LangChain integration for structured LLM interactions
✅ Loads API key securely from .env
✅ Real-time question answering
✅ Simple, lightweight, and easy to extend

🚀 How It Works

User enters a question in the Streamlit input box

The app sends the question to getresponse()

LangChain passes the message to Gemini 2.5-Pro

Gemini returns the AI-generated answer

The response is displayed instantly on the UI

📂 Files in This Repository
File	Description
app.py	Main Streamlit application
.env	Stores your Google API key (GOOGLE_API_KEY=...)
requirements.txt	All required dependencies

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Add your Gemini API key

Create a .env file:

GOOGLE_API_KEY=your_api_key_here

4️⃣ Run the app
streamlit run app.py

💡 Technologies Used

Python 3.10+

Streamlit

LangChain

Google Gemini API (2.5-Pro)

python-dotenv
