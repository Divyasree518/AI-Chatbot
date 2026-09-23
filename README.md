# 🤖 AI Chatbot using GPT-6 Astra

## 📌 Project Description

This project is a simple AI chatbot developed using Python and the GPT-6 Astra API through Kie AI.

The chatbot allows users to interact with the AI through a command-line interface and maintains conversation history during the session.

## ✨ Features

* AI-powered chatbot
* GPT-6 Astra model
* Conversation history
* Command-line interface
* API key protected using `.env`
* Secure API key management using `.gitignore`

## 🛠️ Technologies Used

* Python
* Kie AI API
* GPT-6 Astra
* Requests
* python-dotenv
* Git
* GitHub

## 📂 Project Structure

```text
ai-chatbot/
│
├── app.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-chatbot.git
cd ai-chatbot
```

### 2. Install required packages

```bash
pip install -r requirements.txt
```

### 3. Create the `.env` file

Create a file named `.env` in the project folder.

Add your Kie AI API key:

```env
API_KEY=your_api_key_here
```

### 4. Run the chatbot

```bash
python app.py
```

## 🔐 Security

The API key is stored in the `.env` file and is excluded from Git using `.gitignore`.

The API key must never be uploaded to GitHub or shared publicly.

## 💬 Example
```text
🤖 GPT-6 Astra Chatbot
Type 'exit' to quit

You: Hello
Bot is thinking...

GPT-6 Astra: Hello! How can I help you?

You: What is Python?
Bot is thinking...

GPT-6 Astra: Python is a popular programming language...
```

## 👩‍💻 Author

B Divyasree
