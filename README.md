# Smart-ChatBox
🤖 Hydumiya AI – Flask + Gemini Chat Assistant

A sleek and modern AI chat assistant built using Flask and Google Gemini 2.5 Flash. This project is designed for learning, experimentation, and building next-generation conversational AI applications with a clean UI and real-time responses.

🚀 Features

🔥 Gemini 2.5 Flash powered AI responses  
🧠 Flask backend with REST API  
🎨 Clean and modern chat interface  
⚡ Real-time chat interaction  
🖥️ Localhost deployment ready  
🧩 Beginner-friendly and well-structured project  

📁 Project Structure

├── main.py  
├── templates/  
│   └── index.html  
└── README.md  

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript  
Backend: Python, Flask  
AI Model: Google Gemini 2.5 Flash  
API Client: google-generativeai (genai)  

🔑 Prerequisites

Make sure you have the following installed:

- Python 3.9 or higher  
- pip (Python package manager)  
- Google Gemini API Key  

⚙️ Configuration

Open `main.py` and replace the API key with your own:

```python
client = genai.Client(api_key="YOUR_API_KEY")

🔒 Tip: Never upload your real API key to GitHub.
For production, always use environment variables.

▶️ Run the Application

Install dependencies:

pip install flask google-generativeai


Run the Flask app:

python main.py


The application will start at:

http://127.0.0.1:5000


🧠 How It Works

User sends a message from the chat UI

JavaScript sends the message to the /chat endpoint

Flask forwards the request to Gemini 2.5 Flash

Gemini generates an AI response

The response is displayed instantly in the chat interface

🌱 Future Enhancements

🎤 Voice-based interaction
🧠 Multi-agent AI roles
😄 Emotion-aware responses
🌐 Cloud deployment
🔐 API key management using .env

👨‍💻 Author

Shaik Hydumiya
Data Science Student | AI & GenAI Enthusiast | Flask Developer

🔗 GitHub: https://github.com/shaikhydumiya1127

⭐ Support

If you like this project, please give it a ⭐ on GitHub.
Feel free to fork, improve, and build amazing AI projects on top of it!
