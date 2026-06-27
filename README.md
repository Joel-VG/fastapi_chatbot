# FastAPI Groq Chatbot

A simple AI chatbot built using FastAPI and Groq's Llama 3.3 model. The application provides a ChatGPT-style interface with chat history, dark/light mode, and a responsive user interface.

## Features

- FastAPI backend
- Groq API integration
- ChatGPT-style interface
- Chat history
- New chat option
- Clear chat history
- Dark/Light theme
- Message timestamps
- Copy AI responses
- Responsive design
- Secure API key management using `.env`

## Technologies Used

- Python
- FastAPI
- Groq API
- HTML
- CSS
- JavaScript

## Installation

Clone the repository:

```bash
git clone https://github.com/Joel-VG/fastapi_chatbot.git
cd fastapi_chatbot
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

## Running the Project

Start the FastAPI server:

```bash
fastapi dev project.py
```

Open your browser and go to:

```
http://127.0.0.1:8000
```

## Project Structure

```
fastapi_chatbot/
│
├── static/
│   └── index.html
├── project.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## Usage

1. Run the FastAPI server.
2. Open the application in your browser.
3. Enter a message and click **Send**.
4. Use **New Chat** to start a new conversation.
5. Use **Clear Chats** to remove saved chat history.
6. Switch between **Dark** and **Light** mode using the theme button.

## Future Improvements

- Conversation memory
- Streaming responses
- Voice input
- File upload support
- User authentication

## Author

Joel George
