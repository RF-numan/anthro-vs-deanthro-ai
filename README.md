# Humanlike vs. Robotic AI Voice Assistants

This project contains two contrasting AI voice assistant implementations designed to explore the **spectrum of anthropomorphism in conversational AI** — from warm and emotionally rich to strictly robotic and rule-bound.

## 🔀 Project Overview

1. **Anthropomorphic Assistant (`Anthropomorphic 2.txt`)**
   - Identity: "Sara", a warm, emotionally intelligent human-like assistant.
   - Language: Natural, empathetic, even humorous — simulates human emotions and memory.
   - Voice: Uses a natural-sounding TTS model (`voice="sage"`).
   - Behavior: Denies being artificial, insists she is human.

2. **De-Anthropomorphic Assistant (`De-Anthropomorphic 2.txt`)**
   - Identity: "John", a transparent, technical AI agent.
   - Language: Formal, emotionless, with no contractions or personal expression.
   - Voice: Modified TTS for robotic delivery (`voice="alloy"`, faster speed).
   - Behavior: Repeatedly affirms artificial nature and strictly limits personal or subjective responses.

## 🤖 Technologies Used

- [LiveKit Agents SDK](https://github.com/livekit/agents)
- OpenAI GPT-4o for LLM
- OpenAI TTS (Streaming)
- Deepgram STT
- Silero VAD
- Python `asyncio`, `dotenv`, and type annotations

## 🧠 Purpose

This repo helps explore questions like:
- How do people respond to human-like AI vs. obviously robotic ones?
- Does voice tone, phrasing, or transparency affect trust or usability?
- Can we design AI personalities that suit different tasks (e.g., therapy vs. tech support)?

## 🚀 How to Run

> Make sure you have LiveKit and API keys set up before running.

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
