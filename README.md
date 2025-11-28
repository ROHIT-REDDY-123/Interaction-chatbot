# 🤖 LangChain + Gemini Chat App

A simple Generative AI chat application built with LangChain, Google Gemini (2.5‑Pro), and Streamlit. The app lets users ask questions and receive instant responses powered by Google's Gemini model.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [How It Works](#how-it-works)
- [Files in This Repository](#files-in-this-repository)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project

This project demonstrates how to:

- Connect LangChain with the Google Gemini API.
- Build a reusable function to generate responses from Gemini.
- Create an interactive Q&A chat interface with Streamlit.
- Safely manage API keys using environment variables (.env).
- Deploy a clean and functional AI chatbot with minimal code.

It serves as a beginner-friendly template for creating Gemini-powered Streamlit apps.

---

## Features

- ✅ Clean and intuitive Streamlit UI  
- ✅ Uses Gemini 2.5‑Pro for high-quality responses  
- ✅ LangChain integration for structured LLM interactions  
- ✅ Loads API key securely from `.env`  
- ✅ Real-time question answering  
- ✅ Simple, lightweight, and easy to extend

---

## How It Works

1. The user types a question in the Streamlit input box.  
2. The app sends the question to a `getresponse()` function.  
3. LangChain forwards the message to Gemini 2.5‑Pro.  
4. Gemini returns the AI-generated answer.  
5. The response is displayed instantly in the UI.

---

## Files in This Repository

File | Description
--- | ---
`app.py` | Main Streamlit application
`.env` | Stores your Google API key (e.g. `GOOGLE_API_KEY=...`)
`requirements.txt` | Project dependencies

---

## Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

2. Create and activate a virtual environment (recommended)
```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.venv\Scripts\activate      # Windows
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Add your Gemini API key by creating a `.env` file in the project root:
```env
GOOGLE_API_KEY=your_api_key_here
```

---

## Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

Open the URL shown by Streamlit (usually http://localhost:8501) and start asking questions.

---

## Environment Variables

- `GOOGLE_API_KEY` — Required. Your Google Gemini API key. Keep this secret and do not commit `.env` to version control.

Consider using a secret manager for production deployments.

---

## Technologies Used

- Python 3.10+
- Streamlit
- LangChain
- Google Gemini API (2.5‑Pro)
- python-dotenv

---

