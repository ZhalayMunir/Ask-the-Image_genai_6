# 🎙️🖼️ Ask-the-Image Mini-App

A multimodal proof-of-concept app that lets you **ask questions about images using your voice**, and the AI answers out loud.

Powered by:
- 🧠 Whisper (speech-to-text)
- 🖼️ BLIP-2 (visual question answering)
- 🔊 gTTS (text-to-speech)
- ⚡ Gradio (UI)

---

## 📸 Features

- 🎤 Record or upload your voice to ask a question
- 🖼️ Upload an image
- 🤖 Get an AI-generated answer based on image + question
- 🔈 Listen to the spoken response

---

## 🧪 Models Used

| Task            | Model                             |
|-----------------|------------------------------------|
| Speech-to-Text  | `openai/whisper-small`             |
| VQA             | `Salesforce/blip2-opt-2.7b`        |
| Text-to-Speech  | Google Text-to-Speech (`gTTS`)     |

---

## 🚀 Setup Instructions

### 1. Clone the repository (or download the script)

```bash
git clone https://github.com/your-username/ask-the-image
cd ask-the-image
