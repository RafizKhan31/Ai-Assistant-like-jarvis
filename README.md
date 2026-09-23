# AI Assistant Like  Jarvis From Marvel Movie



Jarvis AI Voice Assistant is a Python-based voice assistant that combines speech recognition, AI-powered responses, text-to-speech, API integrations, and desktop automation. It can process voice commands, interact with AI services, retrieve news and information, open websites, play media, capture screenshots, and perform various automated tasks through an interactive voice interface.

## Features
- Website automation through voice commands
- Screenshot capture automation
- Natural-sounding text-to-speech using Piper TTS
- Interactive conversational assistant workflow
- Voice-activated command system using SpeechRecognition
- AI-generated responses powered by OpenAI API
- Media playback through YouTube Data API
- Real-time news retrieval via NewsData API


## Used Technologies 

**Programming Language**
- Python


**Libraries & Tools**
- SpeechRecognition
- Piper TTS
- PyAutoGUI
- Pygame
- Requests
- Pydub

**APIs**
- OpenAI API
- YouTube Data API v3
- NewsData API

## Project Structure

```
jarvis-ai-assistant/
│
├── main.py
├── config.py
├── requirements.txt
├── README.md
```

## Requirements

- Python 3.9 or higher
- A working microphone for voice input
- Internet connection for API requests

## Installation

1. Clone the repository

```
git clone https://github.com/ttayubudeen/jarvis-ai-assistant.git
```

2. Navigate into the project folder

```
cd jarvis-ai-assistant
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Create a `.env` file and add your API keys

Example:

```
OPENAI_API_KEY=your_api_key_here
NEWS_API_KEY=your_news_api_key
GOOGLE_API_KEY=your_google_api_key
```

5. Run the project

```
python main.py
```


## Author

Md Rafej Khan