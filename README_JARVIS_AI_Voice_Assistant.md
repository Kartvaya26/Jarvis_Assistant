JARVIS – AI Voice Assistant in Python
JARVIS is a voice-controlled personal assistant built using Python. It listens to your voice, understands commands, and performs tasks like opening websites, playing music, fetching the latest news, and even answering questions using AI.

🔧 Features
• Voice recognition using speech-to-text
• Speaks responses using a natural voice
• Opens popular websites like Google, YouTube, Spotify, Reddit, and X (Twitter)
• Plays music from a custom library
• Speaks latest news headlines (via NewsAPI)
• Answers general queries using DeepInfra’s AI API
• Secures API keys with .env file

📦 Requirements
• SpeechRecognition
• pyttsx3
• requests
• python-dotenv
• PyAudio (for microphone support)

🔐 API Setup
Store your API keys in a .env file in the format:
NEWSAPI_KEY=your_key_here
DEEPINFRA_API_KEY=your_key_here

🎵 Music Library
Customize your own music links (YouTube, Spotify, etc.) in a separate file, mapped to simple song names for voice access.

🧠 How It Works
Start the program

Say "Jarvis" to wake it up

Speak your command clearly

JARVIS will respond or perform the task instantly

🎙️ Example Commands
• "Jarvis, open Google"
• "Play Avicii"
• "What is Artificial Intelligence?"
• "Give me the news"
• "Open Spotify"

🗂️ Project Structure
• main.py → Main assistant logic
• musicLibrary.py → Music name and URL map
• .env → Secure API key storage
• README.md → Project documentation

📝 Notes
• Internet is required for online APIs
• Speak clearly and wait for response
• You can expand functionality with custom commands
• Works on Windows and Linux with Python 3.x
