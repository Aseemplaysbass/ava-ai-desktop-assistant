# ava-ai-desktop-assistant
AI-powered desktop assistant with voice control, automation, real-time search, and image generation.

# Ava AI Desktop Assistant

Ava is a Python-based AI desktop assistant capable of performing voice-driven tasks, answering questions using large language models, and automating system operations.

The assistant integrates multiple AI models and APIs to provide conversational responses, real-time web information, image generation, and system automation.

## Features

- Voice-controlled assistant using speech recognition
- AI conversational chatbot powered by Groq LLM
- Query classification using Cohere decision model
- Real-time web search integration
- Desktop automation (open/close applications)
- YouTube and Google search automation
- Image generation using Stable Diffusion API
- Text-to-speech responses using Edge TTS
- GUI-based interface for interaction

## Architecture

The assistant follows a modular pipeline:

Speech Input → Intent Classification → Task Execution

Core components:

- Speech recognition module
- Decision-making model
- Conversational AI chatbot
- Real-time search engine
- Automation engine
- Image generation system
- Text-to-speech module

## Technologies Used

- Python
- Groq LLM API
- Cohere AI
- Stable Diffusion (HuggingFace API)
- Selenium
- Edge TTS
- PyQt GUI
- Asyncio & multithreading

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ava-ai-desktop-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add your API keys:

```
GroqAPIKey=
CohereAPIKey=
HuggingFaceAPIKey=
Username=
Assistantname=
```

Run the assistant:

```
python main.py
```

## Disclaimer

API keys are not included in this repository for security reasons.
