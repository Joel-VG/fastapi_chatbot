# FastAPI Groq Chatbot

A full-stack AI chatbot application powered by FastAPI and Groq's Llama 3.3 model, featuring a clean ChatGPT-style interface, conversation history, and a built-in Dark/Light theme.

## Features

- FastAPI backend
- Groq API integration using Llama 3.3
- ChatGPT-style responsive interface
- Chat history support
- Secure API key handling with `.env`
- Dark/Light theme toggle
- Clean and modern user interface

## Installation

1. Clone the repository:

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project directory and add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

## Run

Start the FastAPI development server:

```bash
fastapi dev project.py
```

Then open your browser and navigate to the local URL displayed in the terminal (typically `http://127.0.0.1:8000`).

## Usage

1. Launch the application.
2. Enter your message in the chat box.
3. Receive AI-generated responses powered by Groq's Llama 3.3 model.
4. View previous messages in the chat history.
5. Click the **Dark/Light Theme** button to switch between dark and light modes.

## Project Structure

```text
.
├── project.py
├── requirements.txt
├── .env
├── templates/
├── static/
└── README.md
```

## Technologies Used

- FastAPI
- Python
- Groq API
- Llama 3.3
- HTML
- CSS
- JavaScript

## License

This project is intended for educational and personal learning purposes.
