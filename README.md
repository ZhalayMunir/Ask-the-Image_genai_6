# 🎙️🖼️ Ask-the-Image Mini-App

A multimodal proof-of-concept app that lets you **ask questions about images using your voice**, and the AI answers out loud.

<img width="1332" height="819" alt="Screenshot 2025-05-01 at 3 04 59 PM" src="https://github.com/user-attachments/assets/31a646c6-94fa-4af5-a9e2-dd36697e39b1" />


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
