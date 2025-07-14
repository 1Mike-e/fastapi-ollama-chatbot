# 🤖 FastAPI Ollama Chatbot

A simple FastAPI application that connects to a local [Ollama](https://ollama.com/) AI model (`mistral`, `llama3`, etc.) to provide a chatbot interface via an HTTP API and static frontend.

---

## 📦 Features

- 🔌 REST API endpoint for chat interaction
- 🧠 Works with local Ollama models like `mistral` or `llama3`
- 🌐 Serves a static HTML frontend from `/static`
- ⚠️ Proper error handling and JSON validation
- 🚀 Easy to run and deploy

---

## 🛠️ Project Structure

├── app.py # FastAPI application
├── static/
│ └── index.html # Frontend HTML served at root "/"
└── README.md


## ⚙️ Requirements

- Python 3.8+
- [Ollama](https://ollama.com/) installed and running locally
- Dependencies from `fastapi`, `uvicorn`, and `requests`

Install with:

```bash
pip install fastapi uvicorn requests
